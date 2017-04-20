# npmdoc-gulp-ruby-sass

#### api documentation for  gulp-ruby-sass (v2.1.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-ruby-sass.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-ruby-sass) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-ruby-sass.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-ruby-sass)

#### Compile Sass to CSS with Ruby Sass

[![NPM](https://nodei.co/npm/gulp-ruby-sass.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-ruby-sass)

- [https://npmdoc.github.io/node-npmdoc-gulp-ruby-sass/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-ruby-sass/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-ruby-sass/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-ruby-sass/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-ruby-sass/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-ruby-sass/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-ruby-sass",
    "version": "2.1.1",
    "description": "Compile Sass to CSS with Ruby Sass",
    "license": "MIT",
    "repository": "sindresorhus/gulp-ruby-sass",
    "maintainers": [
        {
            "name": "Sindre Sorhus",
            "url": "sindresorhus.com"
        },
        {
            "name": "Rob Wierzbowski",
            "web": "robwierzbowski.com"
        }
    ],
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "test": "xo && cd test && mocha test.js"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "keywords": [
        "gulpplugin",
        "scss",
        "sass",
        "css",
        "compile",
        "preprocessor",
        "style",
        "ruby",
        "source-map",
        "source-maps",
        "sourcemap",
        "sourcemaps"
    ],
    "dependencies": {
        "convert-source-map": "^1.0.0",
        "dargs": "^2.0.3",
        "cross-spawn": "^5.0.0",
        "each-async": "^1.0.0",
        "escape-string-regexp": "^1.0.3",
        "glob": "^7.0.3",
        "glob2base": "0.0.12",
        "gulp-util": "^3.0.4",
        "md5-hex": "^1.0.2",
        "object-assign": "^4.0.1",
        "os-tmpdir": "^1.0.0",
        "path-exists": "^2.0.0",
        "rimraf": "^2.2.8"
    },
    "devDependencies": {
        "gulp": "^3.8.11",
        "gulp-sourcemaps": "^2.2.0",
        "mocha": "*",
        "vinyl-file": "^2.0.0",
        "xo": "^0.16.0"
    },
    "xo": {
        "rules": {
            "brace-style": [
                "error",
                "stroustrup",
                {
                    "allowSingleLine": false
                }
            ]
        }
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
