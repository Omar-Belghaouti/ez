<h1 align="center">ez</h1>
<p align="center">interpreted programming language</p>

> pronounced as it's spelled because it's easy 😅

a functional programming language, with first class functions and closures support.

## features

- support the usual data types like strings, booleans, integers, hashes, arrays, and nil

- support the usual operators like `+`, `-`, `*`, `/`, `==`, `!=`, `<`, `>`, and `!`

  - `!` is the logical negation operator
  - `==` is the equality operator
  - `!=` is the inequality operator
  - `<` is the less than operator
  - `>` is the greater than operator
  - `+` is the addition operator
  - `-` is the subtraction operator (unary minus)
  - `*` is the multiplication operator
  - `/` is the division operator

- support the usual flow control operators like `if`, `else`, `let` and `ret`

  - `if` is the conditional operator
  - `else` is the else operator
  - `let` is the let operator
  - `ret` is the return operator (can be omitted)

## syntax

- print a value: `print(value)`
- print a value and a newline: `println(value)
- print a newline: `println()`
- `let` is used to declare a variable: `let variable = value`
- `if` is used to declare a conditional: `if (condition) { // do something }`
- `else` is used to declare an else block: `else { // do something }`
- `ret` is used to return a value: `ret value`
- `f` is used to declare a function: `f(name) { // do something }`
- arrays are declared with `[]`: `[1, 2, 3]`
- hashes are declared with `{}`: `{ "key": "value" }`
- `nil` is used when a value is not present: `nil`

sample code:

```
println("hello world")

let x = 1;
let y = 2;
let z = x + y;
print(z);

let a = "hello";
let b = "world";
let c = a + b;
print(c);

if (x == y) {
    print("x is equal to y");
} else {
    print("x is not equal to y");
}

let d = if (x == y) {
    "x is equal to y"
} else {
    "x is not equal to y"
};
print(d);

let add = f(x, y) {
    ret x + y;
};
print(add(x, y));

let mul = f(x, y) {
    x * y;
};
print(mul(x, y));

let subResult = f(x, y) {
    x - y;
}(x, y);
print(subResult);

let arr = [1, 2, 3, add(x, y), true];
print(arr[0]);

let hash = {
    "key": "value",
    "key2": "value2"
};
print(hash["key"]);
```

## run the interpreter

```sh
go run main.go
```

and start typing in the console 💛
