# jstransformer-slm

[Slm](https://github.com/slm-lang/slm) support for [JSTransformers](http://github.com/jstransformers).

[![Build Status](https://img.shields.io/travis/jstransformers/jstransformer-slm/master.svg)](https://travis-ci.org/jstransformers/jstransformer-slm)
[![Coverage Status](https://img.shields.io/coveralls/jstransformers/jstransformer-slm/master.svg)](https://coveralls.io/r/jstransformers/jstransformer-slm?branch=master)
[![Dependency Status](https://img.shields.io/david/jstransformers/jstransformer-slm/master.svg)](http://david-dm.org/jstransformers/jstransformer-slm)
[![NPM version](https://img.shields.io/npm/v/jstransformer-slm.svg)](https://www.npmjs.org/package/jstransformer-slm)

## Installation

    npm install jstransformer-slm

## API

```js
var slm = require('jstransformer')(require('jstransformer-slm'))

slm.render('p Hello, ${this.name}!', {"name": "World"}).body
//=> '<p>Hello, World!</p>'
```

## License

MIT
