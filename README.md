# test-json
simple utility to function to test if a string is valid JSON or not

```js
var isJSON = require('is-json');

console.log(isJSON('{}')); // => true
console.log(isJSON('{I am not a valid JSON}')); // => false
```
[![NPM][nodei-image]][nodei-url]

[nodei-image]: https://nodei.co/npm/test-json.png?downloads=true&downloadRank=true&stars=true
[nodei-url]: https://www.npmjs.com/package/test-json
