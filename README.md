# npmdoc-react-payment-request-api

#### api documentation for  [react-payment-request-api (v0.1.4)](https://github.com/marcolanaro/react-payment-request-api)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-payment-request-api.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-payment-request-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-payment-request-api.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-payment-request-api)

#### React high order component that expose the payment request api

[![NPM](https://nodei.co/npm/react-payment-request-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-payment-request-api)

- [https://npmdoc.github.io/node-npmdoc-react-payment-request-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-payment-request-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-payment-request-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-payment-request-api/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-payment-request-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-payment-request-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-payment-request-api",
    "version": "0.1.4",
    "description": "React high order component that expose the payment request api",
    "main": "dist/index.js",
    "types": "dist/types.d.ts",
    "scripts": {
        "build": "tsc",
        "tslint": "tslint -c ./tslint.json './src/**/*.ts'",
        "prepublish": "npm run tslint && npm run build"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/marcolanaro/react-payment-request-api.git"
    },
    "bugs": {
        "url": "https://github.com/marcolanaro/react-payment-request-api/issues"
    },
    "homepage": "https://github.com/marcolanaro/react-payment-request-api",
    "keywords": [
        "react",
        "component",
        "payment-request",
        "android-pay",
        "high-order",
        "typescript"
    ],
    "author": "Marco Lanaro <marcolanaro@gmail.com> (https://github.com/marcolanaro)",
    "license": "MIT",
    "devDependencies": {
        "@types/react": "^0.14.41",
        "@types/react-dom": "^0.14.18",
        "pre-commit": "^1.1.3",
        "react": "^15.3.2",
        "react-dom": "^15.3.2",
        "source-map-loader": "^0.1.5",
        "ts-loader": "^0.9.5",
        "tslint": "^3.15.1",
        "typescript": "^2.0.3"
    },
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0-0"
    },
    "pre-commit": [
        "tslint",
        "build"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
