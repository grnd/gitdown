{"gitdown": "badge", "name": "npm-version"}
{"gitdown": "badge", "name": "travis"}
{"gitdown": "badge", "name": "david"}

Gitdown adds [additional functionality](#features) (generating table of contents, including documents, using variables, etc.) to [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/).

## Cheat Sheet

<!-- gitdown: off -->
```js
// Generate table of contents
{"gitdown": "contents"}
{"gitdown": "contents", "maxLevel": 4}
{"gitdown": "contents", "rootId": "features"}

// Use a custom defined variable
{"gitdown": "variable", "name": "nameOfTheVariable"}

// Include file
{"gitdown": "include", "file": "./LICENSE.md"}

// Get file size
{"gitdown": "filesize", "file": "./src/gitdown.js"}
{"gitdown": "filesize", "file": "./src/gitdown.js", "gzip": true}

// Generate badges
{"gitdown": "badge", "name": "npm-version"}
{"gitdown": "badge", "name": "bower-version"}
{"gitdown": "badge", "name": "travis"}
{"gitdown": "badge", "name": "david"}
{"gitdown": "badge", "name": "david-dev"}
{"gitdown": "badge", "name": "waffle"}

// Print date
{"gitdown": "date", "format": "YYYY"}
```
<!-- gitdown: on -->

## Contents

{"gitdown": "contents", "maxDepth": 2}

{"gitdown": "include", "file": "./.README/usage.md"}

## Features

{"gitdown": "include", "file": "./.README/helpers/contents.md"}
{"gitdown": "include", "file": "./.README/helpers/heading-nesting.md"}
{"gitdown": "include", "file": "./.README/helpers/deadlink.md"}
{"gitdown": "include", "file": "./.README/helpers/anchor.md"}
{"gitdown": "include", "file": "./.README/helpers/variable.md"}
{"gitdown": "include", "file": "./.README/helpers/include.md"}
{"gitdown": "include", "file": "./.README/helpers/filesize.md"}
{"gitdown": "include", "file": "./.README/helpers/badge.md"}
{"gitdown": "include", "file": "./.README/helpers/date.md"}
{"gitdown": "include", "file": "./.README/helpers/gitinfo.md"}
