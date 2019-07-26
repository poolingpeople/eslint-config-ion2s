eslint-config-ion2s
===================

> ESLint shareable config for portals maintained by ion2s.


## Installation

```
$ npm i --save-dev eslint-config-ion2s
```


## Usage

This module provides a __base__ shareable config and addition shareable configurations.

Specifying `ion2s` in the `extends` section of your configuration.
```js
module.exports = {
    extends: 'ion2s',
};
```

Feel free to add project specific configuration, like `env` or `parserOptions` - Example:
```js
module.exports = {
    extends: 'ion2s',
    parserOptions: {
        ecmaVersion: 6,
    },
};

```


### AngularJS

Specifying `ion2s/angular-js` in the `extends` section of your configuration.
```js
module.exports = {
    extends: 'ion2s/angular-js',
};
```
