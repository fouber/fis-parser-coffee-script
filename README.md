# fis-parser-coffee-script

A parser plugin for fis to compile coffee script.

## usage

1. Firstly install this plugin: `npm install -g fis-parser-coffee-script`

2. Set this config in the fis-conf.js of **fis3**:

```javascript

fis.match("src/**.coffee", {
  parser: fis.plugin("coffee-script"),
  rExt: ".js"
});

```