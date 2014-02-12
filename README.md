# Util.io [![NPM version][NPMIMGURL]][NPMURL]
[NPMIMGURL]:                https://badge.fury.io/js/util.io.png
[NPM_INFO_IMG]:             https://nodei.co/npm/util.io.png?downloads=true&&stars
[NPMURL]:                   https://npmjs.org/package/util.io "npm"

Util.io - utilites for vanila js. Consist of nice set of functions that works in node and browser.

## Install
For node:
```
npm i util.io
```
For browser:
```html
<script src="lib/util.js"
```

## Api
### exec
Check is parameter is function, if it's - executes it with given parameters

Was:
```js
function(callback, p1, p2, pN) {
    if (typeof callback === 'function')
        callback(p1, p2, pN);
}
```

Now
```js
function(callback, p1, p2, pN) {
    Util.exec(callback, p1, p2, pN);
}
```
