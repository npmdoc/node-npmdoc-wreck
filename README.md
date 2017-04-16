# api documentation for  [wreck (v12.0.0)](https://github.com/hapijs/wreck#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-wreck.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-wreck) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-wreck.svg)](https://travis-ci.org/npmdoc/node-npmdoc-wreck)
#### HTTP Client Utilities

[![NPM](https://nodei.co/npm/wreck.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/wreck)

[![apidoc](https://npmdoc.github.io/node-npmdoc-wreck/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-wreck/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-wreck/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-wreck/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/hapijs/wreck/issues"
    },
    "dependencies": {
        "boom": "4.x.x",
        "hoek": "4.x.x"
    },
    "description": "HTTP Client Utilities",
    "devDependencies": {
        "code": "4.x.x",
        "lab": "13.x.x",
        "require-reload": "0.2.x"
    },
    "directories": {},
    "dist": {
        "shasum": "952684ae83815189f1b3ff4dbdfe2e63d3b65507",
        "tarball": "https://registry.npmjs.org/wreck/-/wreck-12.0.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "73e25e8f06185e07af4c5a32add7b41c18f9d200",
    "homepage": "https://github.com/hapijs/wreck#readme",
    "keywords": [
        "utilities",
        "http",
        "client"
    ],
    "license": "BSD-3-Clause",
    "main": "lib/index",
    "maintainers": [
        {
            "name": "hueniverse"
        },
        {
            "name": "wyatt"
        }
    ],
    "name": "wreck",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/hapijs/wreck.git"
    },
    "scripts": {
        "test": "lab -t 100 -L -a code",
        "test-cov-html": "lab -r html -o coverage.html -a code"
    },
    "version": "12.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module wreck](#apidoc.module.wreck)
1.  [function <span class="apidocSignatureSpan">wreck.</span>emit ()](#apidoc.element.wreck.emit)
1.  number <span class="apidocSignatureSpan">wreck.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">wreck.</span>_defaults
1.  object <span class="apidocSignatureSpan">wreck.</span>_events
1.  object <span class="apidocSignatureSpan">wreck.</span>agents
1.  object <span class="apidocSignatureSpan">wreck.</span>domain



# <a name="apidoc.module.wreck"></a>[module wreck](#apidoc.module.wreck)

#### <a name="apidoc.element.wreck.emit"></a>[function <span class="apidocSignatureSpan">wreck.</span>emit ()](#apidoc.element.wreck.emit)
- description and source-code
```javascript
emit = function () {

    const processEmitter = process[internals.emitSymbol];
    selfEmit.apply(self, arguments);
    processEmitter.emit.apply(processEmitter, arguments);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
