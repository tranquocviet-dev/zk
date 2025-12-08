---
id: JavascriptFunction
aliases:
  - javascript function
tags:
  - javascript
  - l
---
extension from [[Javascript|javascript base]]
[[Function|function]]
functions are reusable code
functions are executed when called
functions are defined before used
```javascript
function name(parameter1, parameter2) {
  codeToBeExecuted;
}
// functions are called with name(arguments)
let value = name(1,2)
```
variables declared inside of functions with [[Let|let]] and [[Const|const]] can not 
be reused outside

[[FunctionParameters|function parameters]]
there may be default values to parameters (to combat unset arguments)
using rest parameter `(...arg)` to allow user to specify an array as arguments
can use `arguments` to call the the arguments value

functions can be called and declared as part of an expression, can be anonymous
still, declaration must come first
> [!NOTE]
> i dont see a point to this rn, will come back if needed

[[FunctionArrow|function arrow]]
shorter syntax for function expressions
```javascript
let something = (a, b) => a * b;
let somethingelse = () => {
  return "hello world";
}
```
