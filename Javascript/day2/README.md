# JavaScript Data Types and Operators

## Boolean

```js
let boolA = true;
let boolB = false;
document.writeln(typeof boolA);
document.writeln(typeof boolB);
```

## null

```js
let nullA = null;
document.writeln(nullA);
```

## undefined

```js
let undefA;
document.writeln(undefA);
```

## Array (typeof returns "object")

```js
let arrA = [1, 2, 3];
document.writeln(typeof arrA);
document.writeln(arrA[0]);
```

## Object

```js
const objA = {
    name: "John",
    age: 30
};
document.writeln(typeof objA);
document.writeln(objA.name);
```

## Arithmetic Operators

The following are common arithmetic operators in JavaScript:

- `+` (Addition)
- `-` (Subtraction)
- `%` (Modulus)
- `/` (Division)
- `*` (Multiplication)
- `++` (Increment)
- `--` (Decrement)
- `**` (Exponentiation)

```js
let numA = 10;
let numB = 20;

document.writeln('sum = ' + (numA + numB));
document.writeln('<br>');
document.writeln('sub = ' + (numA - numB));
document.writeln('<br>');
document.writeln('mul = ' + (numA * numB));
document.writeln('<br>');
document.writeln('div = ' + (numA / numB));
document.writeln('<br>');
document.writeln('mod = ' + (numA % numB));
document.writeln('<br>');
document.writeln('exp = ' + (numA ** 2));
```

## Comparison

Comparison operators: `<`, `>`, `<=`, `>=`, `!=`, `==`, `===`

```js
let compA = 10;
let compB = '20';
if (compA > compB) {
    document.write('hye');
} else {
    document.write('bye');
}
```

## Difference between == and ===

```js
let eqA = 10;
let eqB = '10';
document.writeln(eqA == eqB);  // true
document.writeln(eqA === eqB); // false
```

## Logical Operators

```js
let logA = 10;
let logB = 20;
let logC = 30;

if (logA > logB && logA < logC) {
    document.writeln('Hye');
} else {
    document.writeln('Bye');
}
```

## Bitwise Operators

```js
let bitA = 5;
let bitB = 3;
document.writeln(bitA ^ bitB);
```

## Assignment Operators

Assignment operators: `=`, `+=`, `-=`, `*=`, `/=`, `%=`, `**=`, `<<=`, `>>=`, `>>>=`, `&=`, `|=`, `^=`

```js
let a = 10;
let b = a;
document.writeln(b);
b = 25;
a += b;
document.writeln(a);
```

## Conditional Statements

```js
let a = 100;
if (a > 10) {
    alert('a is greater than 10');
} else {
    alert('a is smaller than 10');
}
```

## Even or Odd Program

```js
let a;
a = prompt("Enter the value of a:");
if (a % 2 == 0) {
  document.writeln("even");
} else {
  document.writeln("odd");
}
```

## Marks Problem

```js
let a = prompt("Enter your marks");
if (a >= 90) {
  document.writeln("You got A");
} else if (a >= 80) {
  document.writeln("You got B");
} else if (a >= 70) {
  document.writeln("You got C");
} else if (a >= 50) {
  document.writeln("You got D");
} else if (a < 40) {
  document.writeln("You got F");
}
```

## Leap Year

```js
let year = prompt('Enter a year:');
year = Number(year);
if ((year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0)) {
    document.writeln('This is leap year');
} else {
    document.writeln('Not leap');
}
```
