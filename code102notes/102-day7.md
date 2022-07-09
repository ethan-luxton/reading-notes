## Programming in Javascript (Day 7 notes)

### Control flow

- Control flow is the order in which a compuer executes statements in a script.

Code is run from the first to last line in any given file, JavaScript is no exception to this. One example is if a user is entering data on a given field, but chooses to enter nothing.

```js
if (field === empty) {
    promptUser();

} else {
    submitForm();
}
```
The above code example is calling two different functions. The first being one where the user is prompted to enter a sumbission. The second is one where the IF statement will submit the form if nothing is entered.

Many languages such as JavaScript, PHP and others use differing control structures for these purposes. Including conditionals such as loops and functions.

### JavaScript Functions

- A JavaScript function is a block of code designed to perform a particular task. It is executed when it is called upon.

Here is an example JavaScript function:

```js
var x = 6; // variable declaration
var y = 3;
function myExample(x, y) { //uses pre determined x and y variables
    return x / y; // returns x divided by y
}
```

- Functions can be used as variable values:

```js
let x = myExample(23);
```

- Functions can also host local variables. These variables do not work outside of the function they are housed in:

```js
function myExample() {
    let x = 1;
}
```

### JavaScript Arithemtic Operators

```
+ 	Addition
- 	Subtraction
* 	Multiplication
** 	Exponentiation (ES2016)
/ 	Division
% 	Modulus (Division Remainder)
++ 	Increment
-- 	Decrement
```

```
=
+=
-=
*=
/=
%=
**=
```

```
==  :   Equal to
=== :   Equal value and equal type
!=  :   Not equal
!== :   Mot equal value and not equal type
>   :   Greater than
<   :   Less than
>=  :   Greater than or equal to
<=  :   Less than or equal to
?   :   Ternary operator
```
```
&&  :   logical and
||  :   logical or
!   :   logical not
```
**JavaScript Bitwise Operators (These work on 32 bit numbers)**
```
& 	AND
| 	OR
~ 	NOT
^ 	XOR
<< 	left shift
>> 	right shift
>>> unsigned right shift
```
[Back to main page](README.md)

