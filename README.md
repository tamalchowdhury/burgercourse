## Number

Any number typed without quotes is a number data type in JavaScript.

```js
let speed = 60
let age = 21
let year = 1999
let PI = 3.1416
let price = 12.99
```

You can use the arithmetic operators on numbers:

```js
let total = 100 + 12
let distance = speed * 5
let birthYear = currentYear - age
let average = totalMarks / numberOfSubjects
```
There are 2 types of number,

### Integer

A whole number. Not a fraction.

All the positive whole numbers from 1, 2, 3, 4.. to Positive Infinity.

All the negative whole numbers from -1, -2, -3, -4.. to Negative Infinity.

And zero 0.

JavaScript used 64 bits to store an integer, 

- so the positive biggest integer is `9007199254740991`
- negative integer is `-9007199254740991` (MDN, 2023)

### Fractions

A real number represented in decimal: `1.2`, `3.1416`, `100.2`.  

JavaScript uses the common `Number` type to store both Integer and Fractions.

References:

- Number, MDN - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number#integer_range_for_number
