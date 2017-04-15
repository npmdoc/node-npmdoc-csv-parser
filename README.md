# api documentation for  [csv-parser (v1.11.0)](https://github.com/mafintosh/csv-parser)  [![npm package](https://img.shields.io/npm/v/npmdoc-csv-parser.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-csv-parser) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-csv-parser.svg)](https://travis-ci.org/npmdoc/node-npmdoc-csv-parser)
#### Streaming CSV parser that aims for maximum speed as well as compatibility with the csv-spectrum test suite

[![NPM](https://nodei.co/npm/csv-parser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/csv-parser)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csv-parser/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csv-parser/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-csv-parser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-csv-parser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "mafintosh"
    },
    "bin": {
        "csv-parser": "./bin.js"
    },
    "bugs": {
        "url": "https://github.com/mafintosh/csv-parser/issues"
    },
    "dependencies": {
        "generate-function": "^1.0.1",
        "generate-object-property": "^1.0.0",
        "inherits": "^2.0.1",
        "minimist": "^1.2.0",
        "ndjson": "^1.4.0"
    },
    "description": "Streaming CSV parser that aims for maximum speed as well as compatibility with the csv-spectrum test suite",
    "devDependencies": {
        "bops": "^0.1.1",
        "concat-stream": "^1.4.5",
        "csv-spectrum": "^1.0.0",
        "standard": "^5.4.1",
        "tape": "^4.2.2"
    },
    "directories": {
        "example": "examples",
        "test": "test"
    },
    "dist": {
        "shasum": "cd92c3f49895a3c1591591035cbfbe6b51c55ab1",
        "tarball": "https://registry.npmjs.org/csv-parser/-/csv-parser-1.11.0.tgz"
    },
    "gitHead": "234c57e330d23cf3c8503417e5436144ef51816a",
    "homepage": "https://github.com/mafintosh/csv-parser",
    "keywords": [
        "csv",
        "parser",
        "fast",
        "json"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mafintosh"
        },
        {
            "name": "maxogden"
        }
    ],
    "name": "csv-parser",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mafintosh/csv-parser.git"
    },
    "scripts": {
        "test": "standard && tape test/test.js"
    },
    "version": "1.11.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module csv-parser](#apidoc.module.csv-parser)
1.  [function <span class="apidocSignatureSpan"></span>csv-parser (opts)](#apidoc.element.csv-parser.csv-parser)
1.  [function <span class="apidocSignatureSpan">csv-parser.</span>toString ()](#apidoc.element.csv-parser.toString)



# <a name="apidoc.module.csv-parser"></a>[module csv-parser](#apidoc.module.csv-parser)

#### <a name="apidoc.element.csv-parser.csv-parser"></a>[function <span class="apidocSignatureSpan"></span>csv-parser (opts)](#apidoc.element.csv-parser.csv-parser)
- description and source-code
```javascript
csv-parser = function (opts) {
  return new Parser(opts)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.csv-parser.toString"></a>[function <span class="apidocSignatureSpan">csv-parser.</span>toString ()](#apidoc.element.csv-parser.toString)
- description and source-code
```javascript
toString = function () {
    return toString;
}
```
- example usage
```shell
...
  }

  return this._onvalue(buf, start, y)
}

Parser.prototype._onvalue = function (buf, start, end) {
  if (this._raw) return buf.slice(start, end)
  return buf.toString('utf-8', start, end)
}

function defaultMapHeaders (id) {
  return id
}

module.exports = function (opts) {
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
