# npmtest-xmldom

#### test coverage for  [xmldom (v0.1.27)](https://github.com/jindw/xmldom)  [![npm package](https://img.shields.io/npm/v/npmtest-xmldom.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-xmldom) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-xmldom.svg)](https://travis-ci.org/npmtest/node-npmtest-xmldom)

#### A W3C Standard XML DOM(Level2 CORE) implementation and parser(DOMParser/XMLSerializer).

[![NPM](https://nodei.co/npm/xmldom.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xmldom)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-xmldom/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-xmldom/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-xmldom/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-xmldom/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-xmldom/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-xmldom/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-xmldom/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-xmldom/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-xmldom/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-xmldom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-xmldom/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-xmldom/build/test-report.html](https://npmtest.github.io/node-npmtest-xmldom/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-xmldom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-xmldom/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-xmldom/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xmldom/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xmldom/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xmldom/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-xmldom/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-xmldom/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "jindw",
        "url": "http://www.xidea.org"
    },
    "bugs": {
        "url": "http://github.com/jindw/xmldom/issues"
    },
    "contributors": [
        {
            "name": "Yaron Naveh",
            "url": "http://webservices20.blogspot.com/"
        },
        {
            "name": "Harutyun Amirjanyan",
            "url": "https://github.com/nightwing"
        },
        {
            "name": "Alan Gutierrez",
            "url": "http://www.prettyrobots.com/"
        }
    ],
    "dependencies": {},
    "description": "A W3C Standard XML DOM(Level2 CORE) implementation and parser(DOMParser/XMLSerializer).",
    "devDependencies": {
        "proof": "0.0.28"
    },
    "directories": {},
    "dist": {
        "shasum": "d501f97b3bdb403af8ef9ecc20573187aadac0e9",
        "tarball": "https://registry.npmjs.org/xmldom/-/xmldom-0.1.27.tgz"
    },
    "engines": {
        "node": ">=0.1"
    },
    "gitHead": "b53aa82a36160d85faab394035dcd1784764537f",
    "homepage": "https://github.com/jindw/xmldom",
    "keywords": [
        "w3c",
        "dom",
        "xml",
        "parser",
        "javascript",
        "DOMParser",
        "XMLSerializer"
    ],
    "licenses": [
        {
            "type": "LGPL",
            "url": "http://www.gnu.org/licenses/lgpl.html",
            "MIT": "http://opensource.org/licenses/MIT"
        }
    ],
    "main": "./dom-parser.js",
    "maintainers": [
        {
            "name": "jindw"
        },
        {
            "name": "yaron"
        },
        {
            "name": "bigeasy"
        },
        {
            "name": "kethinov"
        },
        {
            "name": "jinjinyun"
        }
    ],
    "name": "xmldom",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/jindw/xmldom.git"
    },
    "scripts": {
        "test": "proof platform win32 && proof test */*/*.t.js || t/test"
    },
    "version": "0.1.27"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
