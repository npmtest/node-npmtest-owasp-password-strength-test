# npmtest-owasp-password-strength-test

#### basic test coverage for  owasp-password-strength-test (v1.3.0)  [![npm package](https://img.shields.io/npm/v/npmtest-owasp-password-strength-test.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-owasp-password-strength-test) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-owasp-password-strength-test.svg)](https://travis-ci.org/npmtest/node-npmtest-owasp-password-strength-test)

#### A password-strength tester based upon the OWASP guidelines for enforcing strong passwords.

[![NPM](https://nodei.co/npm/owasp-password-strength-test.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/owasp-password-strength-test)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-owasp-password-strength-test/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-owasp-password-strength-test/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-owasp-password-strength-test/tree/gh-pages/build)|

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
    "name": "owasp-password-strength-test",
    "version": "1.3.0",
    "description": "A password-strength tester based upon the OWASP guidelines for enforcing strong passwords.",
    "main": "owasp-password-strength-test.js",
    "devDependencies": {
        "jshint": "2.6.3",
        "mocha": "2.2.4",
        "should": "3.1.2"
    },
    "jshintConfig": {
        "expr": true,
        "laxbreak": true
    },
    "scripts": {
        "test": "mocha --recursive --reporter spec test.js",
        "lint": "jshint *.js"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/nowsecure/owasp-password-strength-test.git"
    },
    "keywords": [
        "security",
        "password",
        "owasp"
    ],
    "author": "Chris Allen Lane",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
