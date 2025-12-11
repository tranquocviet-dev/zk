---
id: JavascriptObject
aliases:
  - javascript object
tags:
  - javascript
  - l
---
extension from [[Javascript|javascript base]]
[[Object|object]] is a variable that can hold many variables inside itself in the format `key - value`
how to create: 
```javascript
const object {
	firstkey: "1st", 
	secondkey: "2nd",
	thirdkey: "3rd," 
};

const object2 = {};

object2.firstkey = "something";

const object3 = new Object({
	firstkey = "something",  
})
```
parameters in an object can be displayed individually or together as part of the object

[[ObjectConstructor|object constructor]]
```javascript
function createObject (arg1, arg2) {
	this.firstarg = arg1;
	this.secondarg = arg2;
}
```

[[ObjectProperties|object properties]]
properties are the keys and values in object
properties can be added with `object.newproperties = "value"`
properties can be deleted with [[js/Delete|delete]]
properties can be other objects

[[ObjectMethod|object method]]
functions stored inside objects as properties

[[ObjectDisplay|object display]]
methods of displaying an object in different forms
