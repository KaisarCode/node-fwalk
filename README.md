# FWalk
[nodejs] Return files in path.

### Install
```
npm install kc-fwalk
```

### Use
```js
var fwalk = require('kc-fwalk');
var files = fwalk('my-dir');
console.log(files);

// If you don't need to list recursively:
var files = fwalk('my-dir', false);
console.log(files);
```
