phantomas utils
=========

## JS globals survey

This script lets you debug JS globals variables on a given page. Its output is the file and line number where given global is set.

``` bash
phantomjs globals.js --url=https://github.com/macbre/phantomas  --global=GitHub
```

#### Parameters

* `--url` URL of the page to perform survey for
* `--global` name of JS global to look for
