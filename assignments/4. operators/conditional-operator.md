## If Statement
1.  🎖Make a simple calculator with these functions. Using prompt, type conversion, if else statement. Use prompt to take the input from user i.e two numbers and an operation (Add, Sub, Mul, Div).

  ⛑ Rule
    * [ ] While substracting and dividing keep in mind the number one should be greater then number two. If not show alert saying `Number Two is larger then Number one`.
  ⚡️ Operations
    * [ ] Add
    * [ ] Sub
    * [ ] Mul
    * [ ] Div
    <!-- add -->
 var num1 = prompt('enter first number');
 var num2 = prompt('enter second number');
 var add = Number(num1) + Number(num2);
 alert(add);
 <!-- multiply -->
  var multiply = Number(num1) * Number(num2);
 alert(multiply);
<!-- subtract -->
 var num1 = prompt('enter first number');
 var num2 = prompt('enter second number');
  if(num1>num2){
      var sub = Number(num1) - Number(num2);
      alert(sub)
  } else {
   alert('Number Two is larger then Number one')
  }
<!-- divison -->
 if(num1>num2){
      var sub = Number(num1) / Number(num2);
      alert(sub)
  } else {
   alert('Number Two is larger then Number one')
  }

2. 🎖Write a if else statement which checks if the status is single `console.log` the message `John is single` or else `John is married`
```js
var firstName = 'John';
var status = 'single';
// Your code goes here
```
if(status == status){
  console.log(`${firstName} is a single`);
} else {
  console.log(`${firstName} is a married`);
  }

3. 🎖Write a JavaScript program that takes two `integers` from user (using prompt) and alerts the larger number.
```js
// your code goes here
```
  var firstInt = prompt("enter first no");
  var secondInt = prompt("enter second no");
  if(Number(firstInt)>Number(secondInt)){
    alert(firstInt);
  } else {
    alert(Number(secondInt));
  }



4. 🎖Write a JavaScript conditional statement to find the sign (+, -) of product of three numbers. Take those three numbers from user using `prompt`. Display an alert box with the specified sign.

```js
// Your code goes here
```

## Switch Statement

1. 🎖Using switch statement do the following

Take a number value from user and alert the message if it matches the conditions.
* [ ] ONE, if `number` is equal to 1.
* [ ] TWO, if `number` is equal to 2.
* [ ] THREE, if `number` is equal to 3.
* [ ] FOUR, if `number` is equal to 4.
* [ ] FIVE, if `number` is equal to 5.
* [ ] SIX, if `number` is equal to 6.
* [ ] SEVEN, if `number` is equal to 7.
* [ ] EIGHT, if `number` is equal to 8.
* [ ] NINE, if `number` is equal to 9.
* [ ] PLEASE TRY AGAIN, if  is none of the above.
```js
// Your code goes here
```
var userNo =prompt("enter the number");
switch(Number(userNo)) {
  case 1 :
   alert ("one");
   break;
    case 2 :
   alert ("two");
   break;
    case 3 :
   alert ("three");
   break;
    case 4 :
   alert ("four");
   break;
    case 5 :
   alert ("five");
   break;
    case 6 :
   alert ("six");
   break;
    case 7 :
   alert ("seven");
   break;
    case 8 :
   alert ("eight");
   break;
    case 9 :
   alert ("nine");
   break;
   default :
   alert("please try again");
}

2. 🎖Using switch statement do the following

Take the value of `marks` (0-100) from user using `prompt` and `alert` the message (Your Grade is AA) as giver below.
* [ ] `AA` if `marks` is greater than 90.
* [ ] `AB` if `marks` is greater than 80 and less than or equal to 90
* [ ] `BB` if `marks` is greater than 70 and less than or equal to 80
* [ ] `BC` if `marks` is greater than 60 and less than or equal to 70
* [ ] `CC` if `marks` is greater than 50 and less than or equal to 60
* [ ] `CD` if `marks` is greater than 40 and less than or equal to 50
* [ ] `DD` if `marks` is greater than 30 and less than or equal to 40
* [ ] `FF` if `marks` is less than or equal to 30
```js
// Your code goes here
```
var mark = Number(prompt("enter the marks 0-100"));
switch(true) {
  case (mark > 90):
   alert("AA");
   break;
   case (mark > 80 && mark <= 80):
   alert("AB");
   break;
   case (mark > 70 && mark <= 70):
   alert("BC");
   break;
   case (mark > 60 && mark <= 60):
   alert("CC");
   break;
   case (mark > 50 && mark <= 50):
   alert("CD");
   break;
   case (mark > 40 && mark <= 40):
   alert("DD");
   break;
  default :
  alert("FF")
}