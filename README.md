# node-random-stuff
Generate random numbers and strings in node 

Instalation:

`npm install --save dada513/node-random-stuff`

Examples:
```js
const random = require('node-random-stuff')
console.log( random.genNumber(1, 10) ) // returns a random number between 1 and 10
console.log( random.genNumbers(10, 1, 10) ) // returns an array with 10 random numbers between 1 and 10

console.log( random.genString(10) ) // returns a random string with 10 characters
console.log( random.genStrings(5, 10) ) // returns an array of 5 random strings with 10 characters

```