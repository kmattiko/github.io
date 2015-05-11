**Null**  
This is an empty value, nothing is there to represent. The system cannot find what you are looking for 
```
(i.e. var test = x + 2; console.log sample(5))
```
**Boolean**
True and False values. All numbers, aside from 0 will ruturn a true log. 
```
(i.e. 5 + 3 = 8// true) 
```
**Number** 
An intiger representing value 
```
(i.e. 8)
```
**String** 
A phrase or set of letters strung together, can be added to a bigger message posted to console 
```
(i.e."Hello World")
```  
**Infinity**
A numeric representation of the word infinity, which is to say an endless number representing unlimited   potential. JS recognizes this as negative or positive infinity.
```
(i.e. 8 * Infinity = Infinity)
```
**NaN**
This is not a number. It could represent that a math equasion fails and no number is available or it could be a different kind of non-numeric value. 
```
(i.e. 8 + "Hello" = NaN)
```
**Undefined**
This can be when you don't pass your formula a value to work out, JS is waiting for some sort of definition. 
```
(i.e. 8 + x = i)
```  
**Typeof**
This function will check a literal type and identify how it is branded, as in boolean, number, string...ect. 
```
(i.e. typeof Infinity == number)
```
**Binary Operators**
These are systems that look for a left and right side to be added, as in to compare two different things 
```
(i.e. 1 / 2 != 2 / 1 //true)
```
**Length**
The .length property is one in which counts the number or characters or items (especially when it comes to arrays) in a group. It can count the number of items and return it back to the user or it can assign a number to the array. If a bigger number is given the number of items in the array then it doesn't increase the number of items. 
```
var x = y;
y = new array [1, 2, 3];
console.log x.length;
// 3
```
**+**
Adds numbers together to get value 
```
(3 + 5 = 8)
```
**-** 
Subtracts one number from another and produces a remainder 
```
(8 - 5 = 3)
```
**`*`** 
Multiplies, which is to take the value of one number and expand it the number of times of the other number 
```
(3 * 5 = 15)
```
**/**
Divides, which separates one number by another 
```
(15 / 3 = 5)
```
**%** 
Gives the number left over after division has occured 
```
(15 % 8 = 7)
```
**++**
This is the increment operator which will continue adding going up by one until told to stop 
```
(var i = 2; y = x++)
```
**&&**
This represents and, it can be used to check to see if two things are both true seprartly and together 
```
("I like purple" && "I like coffee" // true)
```
**>=** 
Greater or equal 
```
(8 >= 5)
```
**<**
Less than 
```
(5 < 8)
```
**!** 
Not equal to 
```
(8 != 5)
```
**=** 
means "is assigned" as in... 
```
This var x = ("is assigned") y
```
**==**
checks if something "is equal to" something else as in... 
```
"ice cream" == "ice cream"//true , infinity == -infinity//false
```
**Var**
Makes a variable (or identifier) which can be set to rules. Can be started with letters, $, or (_). 
```
(i.e. var hiHello = x)
```
**Return** 
Looks to complete the given task and give results back to the function. It completes the circle in a way. 
```
(i.e. return a + b;)
```
**Array**
This is a group of items that are shown in a list type set. It can be comprised of any kind of items. Items can be called down by number, each item is given an integer starting with 0 and going up. It it represented with square brackets. 
```
var arr = ["Item one", 2, true]
```
**Array.Push**
The .push at the end of the array will take a new element to add into the array and add it to the end. It will also provide a new total length of the given array. 
```
var fruit = ["banana", "orange"];
var fruitTotal = fruit.push ("strawberry")
console.log(fruit) // banana, orange, strawberry
```
**Array.pop**
The .pop will remove the last item within the array, from the array. 
```
 var arr = [1, 2, 3]
 var popped = arr.pop 
 console.log(popped)
// 1, 2
```
**Function** 
This is a way to save bits of code and assign values within the perameters given. This can help us to build working systems that complete certain tasks, depending on what objects the task is given. 
```
function subtraction (a,b){a-b;}subtraction(x,y);
````
**Block Statement**
A block statement is contained wihin a set of curly brackets like so {}. It groups a set of statements or items together. Often an "if" "while, do" or "for" loop will be contained within the block statement. 
```
var i = 1 { i = 2 }// logs i as 2
```
**if/else** 
This is an oporator that can be used within a block. It looks for true or false conditions and applies the correct action. It might read something like "'if' user inputs 'hello' return 'hi'('hello' is true), 'else' user inputs something else return 'I don't know'('hello' is not true)". It would looks something like this. else-if can also be used when more than two arguments are present, as a third or more option. It would be placed between if and else. 
```
if(userInput = "hello" {
return "hello";
}
else {
return "I don't know"
};
```
**switch** 
This is an oporator that can compare several different arguments at the same time to determine which one is true in whichever case given. Within the swtich statement several 'cases' are made, the case which is true will be returned. This can be especially useful when comparing many items, instead of having to use if/else statements. When writing a switch statment it is important to use a 'break' inbetween each case in order for them to separate correctly. It might read something like "user is prompted what the weather is, in the 'case' they state sunny return 'bring sunscreen', in the case they state it is rainy return 'bring an unbrella'"
```
switch(expression) {
 case x:
 return "hello"
 [break;]
 case y:
 return "bye"
 [break;]
}
```
**try/catch**
definition
```
example (hold)
```
**throw**
definition
```
example (hold)
```
**For**
Is a type of function that creates a loop with three specific pieces of information contained within the loop. It contains an initialization (like the start of a function), a condition (telling the system how the function should be run), and a final expression(this tells the system how the function should be counted/expressed). 
```
for(var x = 0, x < 10, x++);
```
**While** 
This allows the system to complete an action as long as (or while) the statement is true. This is helpful to give the system specific times to start and stop. While statements need to have a true and false, one must be placed within the loop and one must be outside. In the example below x is set to be true which allows the while loop to say "hello" until JS reads the line that makes x false, which will stop the while loop from running. 
```
var x = true;
while(x){
	console.log("Hello!");
	x = false;
}
```
**Do/Whil** 
This is a type of loop that continues to run while the statement is true and then stops when it recieves a false. It uses a statement to run the evaluation and a condition to determine how to run the evaluation. It is important to create perameters so that it does not continually recieve true or it will not know when to stop and can create an infinate loop, causing your system to have issues. 
```
var x = 0;
do {
x -= 1;
console log(x);
} while (x > 10);
```
