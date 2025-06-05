# Boolean


let a = true;
let b = false;
document.writeln(typeof a);
document.writeln(typeof b);


# null


let a = null;
document.writeln(a);


# undefined


let a;
document.writeln(a);


# Array (typeof returns "object")


let a = [1, 2, 3];
document.writeln(typeof a);
document.writeln(a[0]);


# Object


const a = {
    name: "John",
    age: 30
};
document.writeln(typeof a);
document.writeln(a.name);


# Arithmetic Operators

The following are common arithmetic operators in JavaScript:

- `+` (Addition)
- `-` (Subtraction)
- `%` (Modulus)
- `/` (Division)
- `*` (Multiplication)
- `++` (Increment)
- `--` (Decrement)
- `**` (Exponentiation)


let a = 10;
let b = 20;

document.writeln('sum = ' + (a + b));
document.writeln('<br>');
document.writeln('sub = ' + (a - b));
document.writeln('<br>');
document.writeln('mul = ' + (a * b));
document.writeln('<br>');
document.writeln('div = ' + (a / b));
document.writeln('<br>');
document.writeln('mod = ' + (a % b));
document.writeln('<br>');
document.writeln('exp = ' + (a ** 2));


# Comparison


// <, >, <=, >=, !=, ==, ===

let a = 10;
let b = '20';
if (a > b) {
    document.write('hye');
} else {
    document.write('bye');
}


# Difference between == and ===


let a = 10;
let b = '10';
document.writeln(a == b);  // true
document.writeln(a === b); // false
