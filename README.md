# is-git-url [![NPM version](https://badge.fury.io/js/is-git-url.png)](http://badge.fury.io/js/is-git-url)

> Regex to validate that a URL is a git url.

See <http://git-scm.com/book/ch4-1.html> for more info.

## Install
Install with [npm](npmjs.org):

```bash
npm i is-git-url --save-dev
```


## Usage

```js
var isGitUrl = require('is-git-url');
console.log(isGitUrl('git://github.com/jonschlinkert/is-git-url.git'));
//=> true
console.log(isGitUrl('https://github.com/jonschlinkert/'));
//=> false
```

Edit on [debuggex](https://www.debuggex.com/r/WeYxcD7Ghp5ekrPR/0#cheatsheet)

![image](https://cloud.githubusercontent.com/assets/383994/2627089/bd37da5c-bdf9-11e3-9c26-d2b02f46bc24.png)


## Author

**Jon Schlinkert**

+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

## License
Copyright (c) 2014 Jon Schlinkert, contributors.  
Released under the MIT license

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on April 06, 2014._