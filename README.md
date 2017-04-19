# npmtest-react-native-router-flux

#### test coverage for  [react-native-router-flux (v3.38.0)](https://github.com/aksonov/react-native-router-flux#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-native-router-flux.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-native-router-flux) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-native-router-flux.svg)](https://travis-ci.org/npmtest/node-npmtest-react-native-router-flux)

#### React Native Router using Flux architecture

[![NPM](https://nodei.co/npm/react-native-router-flux.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-native-router-flux)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-native-router-flux/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-native-router-flux/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-native-router-flux/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-native-router-flux/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-native-router-flux/build/test-report.html](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-native-router-flux/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-native-router-flux/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-native-router-flux/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-native-router-flux/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-native-router-flux/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Pavlo Aksonov",
        "url": "http://aksonov.com"
    },
    "bugs": {
        "url": "https://github.com/aksonov/react-native-router-flux/issues"
    },
    "dependencies": {
        "react-native-experimental-navigation": "0.26.x",
        "react-native-tabs": "^1.0.9",
        "react-static-container": "1.0.1"
    },
    "description": "React Native Router using Flux architecture",
    "devDependencies": {
        "babel-core": "^6.18.2",
        "babel-eslint": "^7.1.1",
        "babel-jest": "19.0.0",
        "babel-preset-es2015": "^6.22.0",
        "babel-preset-react-native": "^1.9.0",
        "babel-preset-stage-0": "^6.22.0",
        "chai": "^3.5.0",
        "chai-as-promised": "^6.0.0",
        "enzyme": "^2.6.0",
        "eslint": "^3.11.0",
        "eslint-config-airbnb": "^13.0.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^2.2.3",
        "eslint-plugin-react": "^6.7.1",
        "expect": "^1.20.2",
        "jest": "19.0.1",
        "mocha": "^3.2.0",
        "mocha-junit-reporter": "^1.12.1",
        "react-native-mock": "0.2.0",
        "react-test-renderer": "15.4.2",
        "sinon": "^1.17.6"
    },
    "directories": {},
    "dist": {
        "shasum": "f5f8ec2875b46f96f61006ff502d0d80268e6ce2",
        "tarball": "https://registry.npmjs.org/react-native-router-flux/-/react-native-router-flux-3.38.0.tgz"
    },
    "gitHead": "4f91ad57563553c98530cd5841ad27a048f4f582",
    "homepage": "https://github.com/aksonov/react-native-router-flux#readme",
    "jest": {
        "preset": "react-native"
    },
    "keywords": [
        "react-native",
        "react-native-router",
        "react-components",
        "react-component",
        "ios",
        "android",
        "flux",
        "router",
        "navigation"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "aksonov"
        }
    ],
    "name": "react-native-router-flux",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/aksonov/react-native-router-flux.git"
    },
    "scripts": {
        "eslint": "eslint index.js src/ test/; exit 0;",
        "test": "mocha --compilers js:babel-core/register --require react-native-mock/mock",
        "test:watch": "npm run test -- --watch"
    },
    "typings": "index.d.ts",
    "version": "3.38.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
