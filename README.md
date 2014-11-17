karma-sinon-chai-latest
=======================

[sinon-chai](https://github.com/domenic/sinon-chai) for [Karma](http://karma-runner.github.io)

[![NPM version](https://badge.fury.io/js/karma-sinon-chai-latest.png)](http://badge.fury.io/js/karma-sinon-chai-latest) [![Dependency status](https://david-dm.org/directxman12/karma-sinon-chai-latest.png)](https://david-dm.org/directxman12/karma-sinon-chai-latest) [![devDependency Status](https://david-dm.org/directxman12/karma-sinon-chai-latest/dev-status.png)](https://david-dm.org/directxman12/karma-sinon-chai-latest#info=devDependencies)

Based off of the [karma-chai](https://github.com/xdissent/karma-chai) package.

Installation
------------

Install the plugin from npm:

```sh
$ npm install karma-sinon-chai-latest --save-dev
```

Or from Github:

```sh
$ npm install 'git+https://github.com/directxman12/karma-sinon-chai-latest.git' --save-dev
```

Add `sinon-chai` to the `frameworks` key in your Karma configuration:

```javascript
module.exports = function (config) {
    config.set({
        frameworks: ['mocha', 'chai', 'sinon-chai']

        # ...
    });
});
```


Usage
-----

All of the various sinon-chai assertions are available as normal.

License
-------

The MIT License (MIT)
