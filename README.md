eslint-plugin-variables
=================

ESLint micro plugin with rules for more strictly variables usage.

Usage
-----

Add into your `.eslintrc`:
```json
{
  "plugins": [
    "variables"
  ],
  "rules": {
    "variables/only-ascii-variables": "error"
  }
}
```

Rules list
----------

Currently following rules is supported:

  - `es5/only-ascii-variables`: Forbid [unicode variable names](https://mathiasbynens.be/notes/javascript-identifiers).

License
-------
[MIT](LICENSE)