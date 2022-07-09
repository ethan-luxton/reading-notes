## Operators and loops (Day 8 Notes)

I touched a bit on operators in my previous notes on day 7, however, there is much, much, much more to them. There are several types of operators, all of which serve a different purpose:

1. Assignment operators
2. Comparison operators
3. Arithmetic operators
4. Bitwise operators
5. Logical operators
6. String operators
7. Conditional (ternary) operators
8. Comma operators
9. Unary operators
10. Relational operators

I will give some examples of each of the ones I did not cover in my [day 7 notes](day7.md).

### String operators -

String operators can be used on string values this includes such operators as (+) to combine two strings together.

```js
// console.log example:
console.log('my' + 'example');
// variable example:
var myExample = 'test';
console.log(myExample += 'ing');
//output: testing
```

### Conditional (ternary) operators -

The conditional operator is the only JavaScript operator that takes three operands.

For example:

```js
let status = (age >= 21) ? 'legal to drink' : 'not legal to drink';
// this variable would now have two outputs depending on the input, either legal to drink or not legal to drink
```

### Comma operator -

Comma operators evaluate both operands and return the value of the last one. It is primarily used in for loops. 

Example for an array (not a 102 concept):

```js
var x = [0,1,2,3,4,5,6,7,8,9]
var a = [x, x, x, x, x];

for (var i = 0, j = 9; i <= j; i++, j--)
//                                ^
  console.log('a[' + i + '][' + j + ']= ' + a[i][j]);
```

### Unary operators -

Unary operators only have one operand: **delete**. This deletes an objects property.

```js
delete object.property;
delete object[property];
delete objectName[test];
```

### Relational operators -

Finally, relational operators. Relational operators compare operands and returns a boolean value based on true.

```js
testNameOrNumber in objectTest
```

## Loops and iteration

There are a few different types of loops, but here is a quick rundown of them:

```js
//for loops
for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}
```
```js
//do...while statement
do
    statement
while(condition);
```
```js
//while statement
while (condition)
    statement
```
```js
//labeled statement
markLoop:
while (theMark === true) {
   doSomething();
}
```
```js
//break statement
for (let i = 0; i < a.length; i++) {
  if (a[i] === theValue) {
    break;
  }
}
```
```js
//continue statement
continue [markloop];
//this would continue the labeled statement above while theMark === true 
```
*And second to last*, the for...in statement:
```js
for (variable in object)
  statement
```
*And lastly*, the for...of statement:
```js
for (variable of object)
  statement
```
[Back to main page](README.md)

