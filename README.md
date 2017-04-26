# npmtest-owasp-password-strength-test

#### basic test coverage for  [owasp-password-strength-test (v1.3.0)](https://github.com/nowsecure/owasp-password-strength-test)  [![npm package](https://img.shields.io/npm/v/npmtest-owasp-password-strength-test.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-owasp-password-strength-test) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-owasp-password-strength-test.svg)](https://travis-ci.org/npmtest/node-npmtest-owasp-password-strength-test)

#### A password-strength tester based upon the OWASP guidelines for enforcing strong passwords.

[![NPM](https://nodei.co/npm/owasp-password-strength-test.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/owasp-password-strength-test)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-owasp-password-strength-test/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-owasp-password-strength-test/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/test-report.html](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-owasp-password-strength-test/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-owasp-password-strength-test/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-owasp-password-strength-test/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-owasp-password-strength-test/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Chris Allen Lane"
    },
    "bugs": {
        "url": "https://github.com/nowsecure/owasp-password-strength-test/issues"
    },
    "dependencies": {},
    "description": "A password-strength tester based upon the OWASP guidelines for enforcing strong passwords.",
    "devDependencies": {
        "jshint": "2.6.3",
        "mocha": "2.2.4",
        "should": "3.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "4f629e42903e8f6d279b230d657ab61e58e44b12",
        "tarball": "https://registry.npmjs.org/owasp-password-strength-test/-/owasp-password-strength-test-1.3.0.tgz"
    },
    "gitHead": "a8545f211fd90108fc976c31ff53fbf0d5316be2",
    "homepage": "https://github.com/nowsecure/owasp-password-strength-test",
    "jshintConfig": {
        "expr": true,
        "laxbreak": true
    },
    "keywords": [
        "security",
        "password",
        "owasp"
    ],
    "license": "MIT",
    "main": "owasp-password-strength-test.js",
    "maintainers": [
        {
            "name": "chrisallenlane"
        }
    ],
    "name": "owasp-password-strength-test",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nowsecure/owasp-password-strength-test.git"
    },
    "scripts": {
        "lint": "jshint *.js",
        "test": "mocha --recursive --reporter spec test.js"
    },
    "version": "1.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
