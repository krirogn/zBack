# Language files

### Intro
In zBack you have to use `.po` files to write language files
filled with the strings and identifiers of all the text in the backend.

### How To Use
To use the language strings in code use the `$catalog->getEntry('identifier')->getMsgStr()` syntax.

### Example use
`
http_response_code(403);
die($catalog->getEntry('authTimeout')->getMsgStr());
`