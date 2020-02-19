1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
```
<!-- name is a var-->

2. Find the error if any
```js
  var product cost = 3.45;
```
<!-- space between product and const -->
3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" 
  //right
  'Hello World" 
  // wrong
  "Hello World'
  // wrong
  'Hello World'
  // right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; //valid
var 1girl; //Invalid
var woman3; //valid
var -girl; //invalid
var blackDog; //valid
var 42; //invalid
var $42;//invalid
var userName; //valid
var x, y, z;  //valid
var x = 5, y = 6, z = 7;//invalid
var x = 5 + 10 + 2; //invalid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
var value = (amount - 80)
alert (value);
 var val2 = (amount +200);
 alert(val2);
 var val3 = (amount * 4);
 console.log(val3);
 var val4 = (amount/ 21);
 console.log(val4);
// Define a new variable and store the value that is 80 less then the value of amount.

// Define a new variable and store the value that is 200 more then the value of amount.

// Define a new variable and store the value that is 4 times the value of amount.

// Define a new variable and store the reminder when the value of amount is  divided by 21.
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;
if (johnAge > markAge  ||  markAge < johnAge){
  console.log("elder")
}
// Check who is older eithe John or Mark
// Check who is younger
if ( markAge < johnAge  ||  johnAge > markAge ){
  console.log("yonger")
}
// Check if their age is equal
if (johnAge == markAge  ||  markAge == johnAge){
  console.log("equl")
} else {
    console.log("not equal")
}
// Create a new variable and assign the age of john to new variable.
// Check if john is equal to or greater then mark.
// Check if john is less then or equal to mark.
// Calculate the average age of john and mark and assign to a new variable.
let newAge = johnAge;
if(newAge >= markAge || newAge<= markAge){
  var avg = newAge + markAge;
console.log(avg)
}
```