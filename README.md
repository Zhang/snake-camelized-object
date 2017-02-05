## snakeys -- transform a string to snakecase

Recursively transform an object's keys from camelCase to snake_case

## Install

```
$ npm install --save snake-camelized-object
```

## Usage

```javascript
var snakeys = require('snake-camelized-object');

snakeys({ deep: { Ly: { nesTed: 'obj' } } }) //  { deep: { Ly: { nes_ted: 'obj' } } }
snakeys({ wUt: {}, the: '', javaScript: null }) //   { w_ut: {}, the: '', java_script: null }
```
