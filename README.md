# npmtest-torrent-stream

#### basic test coverage for  [torrent-stream (v1.0.3)](https://github.com/mafintosh/torrent-stream)  [![npm package](https://img.shields.io/npm/v/npmtest-torrent-stream.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-torrent-stream) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-torrent-stream.svg)](https://travis-ci.org/npmtest/node-npmtest-torrent-stream)

#### Low level streaming torrent client that exposes files as node.js streams and downloads pieces based on demand

[![NPM](https://nodei.co/npm/torrent-stream.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/torrent-stream)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-torrent-stream/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-torrent-stream/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-torrent-stream/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-torrent-stream/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-torrent-stream/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-torrent-stream/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-torrent-stream/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-torrent-stream/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-torrent-stream/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-torrent-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-torrent-stream/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-torrent-stream/build/test-report.html](https://npmtest.github.io/node-npmtest-torrent-stream/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-torrent-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-torrent-stream/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-torrent-stream/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-torrent-stream/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-torrent-stream/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-torrent-stream/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-torrent-stream/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-torrent-stream/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/mafintosh/torrent-stream/issues"
    },
    "dependencies": {
        "bitfield": "^0.1.0",
        "bncode": "^0.5.2",
        "end-of-stream": "^0.1.4",
        "fs-chunk-store": "^1.3.0",
        "hat": "0.0.3",
        "immediate-chunk-store": "^1.0.5",
        "ip-set": "^1.0.0",
        "mkdirp": "^0.3.5",
        "parse-torrent": "^4.0.0",
        "peer-wire-swarm": "^0.12.0",
        "rimraf": "^2.2.5",
        "torrent-discovery": "^5.2.0",
        "torrent-piece": "^1.0.0"
    },
    "description": "Low level streaming torrent client that exposes files as node.js streams and downloads pieces based on demand",
    "devDependencies": {
        "bittorrent-tracker": "^2.6.0",
        "fs-extra": "^0.26.4",
        "standard": "^5.1.0",
        "tap": "^0.4.8"
    },
    "directories": {},
    "dist": {
        "shasum": "d8c043b44c3c448c9397a3aec42d2df55887037b",
        "tarball": "https://registry.npmjs.org/torrent-stream/-/torrent-stream-1.0.3.tgz"
    },
    "gitHead": "025bd62df93cd0accccd720f28209770424aa4f2",
    "homepage": "https://github.com/mafintosh/torrent-stream",
    "maintainers": [
        {
            "name": "mafintosh"
        },
        {
            "name": "ralphtheninja"
        }
    ],
    "name": "torrent-stream",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/mafintosh/torrent-stream.git"
    },
    "scripts": {
        "test": "standard && tap test/*.js"
    },
    "version": "1.0.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
