# api documentation for  [grunt-spritesmith (v6.4.0)](https://github.com/Ensighten/grunt-spritesmith)  [![npm package](https://img.shields.io/npm/v/npmdoc-grunt-spritesmith.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-grunt-spritesmith) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-grunt-spritesmith.svg)](https://travis-ci.org/npmdoc/node-npmdoc-grunt-spritesmith)
#### Grunt task for converting a set of images into a spritesheet and corresponding CSS variables.

[![NPM](https://nodei.co/npm/grunt-spritesmith.png?downloads=true)](https://www.npmjs.com/package/grunt-spritesmith)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-spritesmith/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-grunt-spritesmith_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-spritesmith/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-grunt-spritesmith/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-grunt-spritesmith/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Todd Wolfson",
        "email": "todd@twolfson.com",
        "url": "http://twolfson.com/"
    },
    "bugs": {
        "url": "https://github.com/Ensighten/grunt-spritesmith/issues"
    },
    "contributors": [
        {
            "name": "dpolivy"
        },
        {
            "name": "pdehaan",
            "url": "http://about.me/peterdehaan"
        },
        {
            "name": "MoOx",
            "email": "github@moox.io",
            "url": "http://moox.io/"
        },
        {
            "name": "jasonsandmeyer",
            "url": "http://jasonsandmeyer.com"
        },
        {
            "name": "scanieso",
            "email": "scanieso@gmail.com"
        },
        {
            "name": "STuFF",
            "email": "nchalleil@gmail.com"
        }
    ],
    "dependencies": {
        "async": "~1.5.0",
        "spritesheet-templates": "~10.2.0",
        "spritesmith": "~3.1.0",
        "underscore": "~1.4.2",
        "url2": "1.0.0"
    },
    "description": "Grunt task for converting a set of images into a spritesheet and corresponding CSS variables.",
    "devDependencies": {
        "foundry": "~4.3.2",
        "foundry-release-git": "~2.0.2",
        "foundry-release-npm": "~2.0.2",
        "get-pixels": "~3.2.3",
        "gmsmith": "~1.0.0",
        "grunt": "~0.4.2",
        "grunt-cli": "~0.1.13",
        "grunt-newer": "~0.8.0",
        "js-yaml": "~3.2.3",
        "jscs": "~1.8.1",
        "jshint": "~2.5.10",
        "mocha": "~1.21.5",
        "rimraf": "~2.2.8",
        "shell-quote": "~1.4.2",
        "twolfson-style": "~1.6.0"
    },
    "directories": {},
    "dist": {
        "shasum": "1335222e5fc3ca86acce608a852eba759b0d873a",
        "tarball": "https://registry.npmjs.org/grunt-spritesmith/-/grunt-spritesmith-6.4.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "foundry": {
        "releaseCommands": [
            "foundry-release-git",
            "foundry-release-npm"
        ]
    },
    "gitHead": "681652cfa6f48ffdf7e69875458e70438a4ebca3",
    "homepage": "https://github.com/Ensighten/grunt-spritesmith",
    "keywords": [
        "grunt",
        "gruntplugin",
        "sprite",
        "image",
        "spritesheet",
        "css",
        "spritesmith",
        "cross-platform"
    ],
    "license": "MIT",
    "main": "tasks/grunt-spritesmith.js",
    "maintainers": [
        {
            "name": "twolfson",
            "email": "todd@twolfson.com"
        }
    ],
    "name": "grunt-spritesmith",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/Ensighten/grunt-spritesmith.git"
    },
    "scripts": {
        "lint": "twolfson-style lint docs/ src/ src-test/ tasks/",
        "precheck": "twolfson-style precheck docs/ src/ src-test/ tasks/",
        "pretest": "twolfson-style install",
        "test": "npm run precheck && mocha src-test/ --reporter dot --timeout 5000 && npm run lint"
    },
    "version": "6.4.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module grunt-spritesmith](#apidoc.module.grunt-spritesmith)



# <a name="apidoc.module.grunt-spritesmith"></a>[module grunt-spritesmith](#apidoc.module.grunt-spritesmith)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
