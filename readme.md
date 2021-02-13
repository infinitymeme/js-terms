# JS TERMS
Press `Ctrl + Shift + V` in VSCode to preview as a formatted markdown document.

---
---
## Initialization
> creation of a new variable

**Symbols:** `let`, `const`, `var`

---
### Example 1: Normal variable
```js
let myVariable;
```
### Example 2: Variable that cannot be redefined
```js
const myVariable;
```
### Example 3: Normal variable (outdated)
*(do not use unless specifically required)*
```js
var myVariable;
``` 

---
---
## Definition
> giving a variable a value (for the first time)

**Symbols:** `=`

---
### Example 1: definition later
```js
let myVariable; // initialization
myVariable = "hello!"; // definition
```
### Example 2: definition at the same time
```js
let myVariable = "hello!"; // initialization + definition
```
### Example 3: definition of different variable types
```js
let myNumber = 0; //number variable, can use for math
let myString = ""; //string variable, holds text data
let myArray = []; //array variable, holds other data or variables
let myObject = {}; //object, holds other data or variables AND labels them
```
How about we give them some values too?
```js
let myNumber = 5; //number variable, can use for math
let myString = "hello!"; //string variable, holds text data
let myArray = [1, "stick", myNumber, [5,6,7]]; //array variable, holds other data or variables
let myObject = {name:"John", money:100}; //object, holds other data or variables AND labels them
```
### Example 4: definition of a function
```js
function myFunction() {
    //run some code
}
```
What about one with parameters and a return statement?
```js
function shout(sender, message) {
    return sender+" says "+message.toUpperCase()+"!";
}
shout("Bob","i like turtles"); // returns "Bob says I LIKE TURTLES!"
```

---
---
## Redefinition
> giving a variable a value that overwrites a previous definition
    
**Symbols:** `=`

---
### Example 1: basic redefinition
```js
let myVariable = "hello!"; // initialization + definition
myVariable = "goodbye!"; // redefinition
```

---
---
## Indexing
> pulling a value out of an array by its position

**Symbols:** `arrayName[☆]`

(☆ is an epression that evaluates to a number)

---
### Example 1: basic indexing
```js
let myArray = [5,4,3];
myArray[0] // produces 5, AKA the item at index 0
```
### Example 2: indexing using a variable
```js
let myArray = [5,4,3];
let index = 1;
myArray[index] //produces 4, AKA the item at index 1
```
### Example 3: indexing from the end
```js
let myArray = [5,4,3];
myArray[index.length-1] //produces 3, AKA the item at the last index
```

---
---
## Calling
> running the code of a function

**Symbols:** `functionName(☆)`

(☆ is appropriate inputs for the function)

---
### Example 1: console.log is a function!
```js
console.log("words");
//BREAKDOWN:
// console    - using the console object
// .          - access the
// log        - log function
// ("words")  - and CALL it with the data "words"
```

---
---
## Accessing
> using a variable or method attached to an object or variable

**Symbols:** `.`

---
### Example 1: array size
```js
let myArray = [1,2,3];
myArray.length;
//BREAKDOWN:
// myArray  - using myArray variable
// .        - ACCESS the
// length   - length variable
```
### Example 2: console object
```js
console.log();
//BREAKDOWN:
// console  - using the console object
// .        - ACCESS the
// log      - log function
// ()       - and call it
``` 
