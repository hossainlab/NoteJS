<h2 align="center">Notes For Learning JavaScript</h2>

### `Variables`
**There are there ways to create variable**
- Using `var` Keyword 
- Using `let` Keyword 
- Using `const` Keyword 

### `Examples`
```javascript
// Using `var` Keyword 
var name = "Jubayer Hossain"; 
console.log(name);
// Output: Jubayer Hossain

// Using `let` Keyword 
let name = "Tasmim Adib"; 
console.log(name); 
// Output: Tasmim Adib

// Using `const`
const pi = 3.1416; 
console.log(pi); 
// Output: 3.1416
```
### `Difference Between Three` 
```javascript
// INIT A VARIABLE WITH `var`
// Assign a value into `a`  
var a = 10; 
console.log(a); 
// Output: 10 
// Re-assign a value into `a` 
a = 15; 
console.log(a);
// Output: 15 
```
```javascript
// INIT A VARIABLE WITH `let` 
// Assign a value into `num`
let num = 30; 
console.log(num); 
// Output: 30 
// Re-assign value into `num`
num = 42; 
console.log(num);
// Output: 42
```

```javascript
// INIT A VARIABLE WITH `const`
// Assign 
const g = 9.81; 
console.log(g);
// Output: 9.81 
// Re-assign 
g = 9.78; 
console.log(g);
// Output: TypeError: Assignment to constant variable.
```
> Note: We can reassign value for `var` and `let` but not `const`.