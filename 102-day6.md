## Intro to JavaScript (Day 6)

JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. 

Unlinke HTML and CSS, Javascript focuses more on the logic and mathematical side of a web page. This is achieved through a variety of variables, operators, conditionals, functions, and events.

Here are some examples of code for each of these:

### Variables

```js
var example = example // can be redeclared and reassigned, however, it is not recommended to redeclare it
let example = example // cannot be redeclared
const example = example // cannot be reassigned
```

### Operators

```js
+ // addition
-, *, / // subtraction, multiplication and division
===, ==, = // strict equality, loose equality, equality
!, !== //not and does-not-equal
```

### Conditionals
```js
// example code
let iceCream = 'chocolate';
if(iceCream === 'chocolate') {
  alert('Yay, I love chocolate ice cream!');
} else {
  alert('Awwww, but chocolate is my favorite...');
}
```

### Functions

```js
// example code
document.write('Hello ' + firstName + '!' + message); // displays "Hello (firstname)! (message)
```
### Events

```js
// example code
document.querySelector('html').addEventListener('click', function() {
  alert('Ouch! Stop poking me!'); // brings up an alert on the webpage 
});
```
[Back to main page](day6.md)