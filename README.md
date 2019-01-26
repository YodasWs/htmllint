htmllint
========

[![npm version](http://img.shields.io/npm/v/@yodasws/htmllint.svg?style=flat-square)](https://npmjs.org/package/@yodasws/htmllint)
[![license](http://img.shields.io/npm/l/@yodasws/htmllint.svg?style=flat-square)](https://npmjs.org/package/@yodasws/htmllint)
[![dependencies](http://img.shields.io/david/yodasws/htmllint.svg?style=flat-square)](https://david-dm.org/yodasws/htmllint)
[![devDependencies](http://img.shields.io/david/dev/yodasws/htmllint.svg?style=flat-square)](https://david-dm.org/yodasws/htmllint)

> An unofficial html5 linter and validator.

htmllint uses a parser to get the DOM for your html. It then uses the provided rules (and default rules) to lint both the DOM and then individual lines.

Using htmllint
--------------
This module doesn't provide any interface on its own. If you're using gulp, use the folloiwing module:
* [`gulp-htmllint`](https://github.com/yodasws/gulp-html-lint): a gulp interface for htmllint

Getting Started with Contributing
---------------
You can use htmllint in Node.JS by using
```
require('@yodasws/htmllint')
```
in your code, and doing an install with
```
yarn add @yodasws/htmllint
```

[![npm](https://nodei.co/npm/@yodasws/htmllint.png)](https://npmjs.org/package/@yodasws/htmllint)
