1. Built-in objects
  * Null -  This is an empty value, nothing is there to represent. The system cannot find what you are looking for (i.e. var test = x + 2; console.log sample(5))
  * Boolean - True and False values. All numbers, aside from 0 will ruturn a true log. (i.e. 5 + 3 = 8// true) 
  * Number - An intiger representing value (i.e. 8)
  * String - A phrase or set of letters strung together, can be added to a bigger message posted to console (i.e."Hello World")
  * Infinity - A numeric representation of the word infinity, which is to say an endless number representing unlimited   potential. JS recognizes this as negative or positive infinity.(i.e. 8 * Infinity = Infinity)
  * NaN - This is not a number. It could represent that a math equasion fails and no number is available or it could be a different kind of non-numeric value. (i.e. 8 + "Hello" = NaN)
  * Undefined - This can be when you don't pass your formula a value to work out, JS is waiting for some sort of definition. (i.e. 8 + x = i)
  * Typeof - This function will check a literal type and identify how it is branded, as in boolean, number, string...ect. (i.e. typeof Infinity == number)
  * Binary Operators- these are systems that look for a left and right side to be added, as in to compare two different things (i.e. 1 / 2 != 2 / 1 //true)
  * Length - the .length property is one in which counts the number or characters or items (especially when it comes to arrays) in a group. It can count the number of items and return it back to the user or it can assign a number to the array. If a bigger number is given the number of items in the array then it doesn't increase the number of items. 
 ````
var x = y;
y = new array [1, 2, 3];
console.log x.length;
// 3
````
2. Arithmetic Operators
  * + - Adds numbers together to get value (3 + 5 = 8)
  * - - Subtracts one number from another and produces a remainder (8 - 5 = 3)
  * * - Multiplies, which is to take the value of one number and expand it the number of times of the other number (3 * 5 = 15)
  * / - Divides, which separates one number by another (15 / 3 = 5)
  * % - Gives the number left over after division has occured (15 % 8 = 7)
  * ++ - this is the increment operator which will continue adding going up by one until told to stop (var i = 2; y = x++)
  * && - this represents and, it can be used to check to see if two things are both true seprartly and together ("I like purple" && "I like coffee" // true)
3. Comparison Operators
  * >= - Greater or equal (8 >= 5)
  * < - Less than (5 < 8)
  * != - Not equal to (8 != 5)
  * = means "is assigned" as in... This var x = ("is assigned") y
  * == checks if something "is equal to" something else as in... "ice cream" == "ice cream"//true , infinity == -infinity//false
4. Statements and Declarations
  *  Var - Makes a variable (or identifier) which can be set to rules. Can be started with letters, $, or (_). (i.e. var hiHello = x)
  *  Return - Looks to complete the given task and give results back to the function. It completes the circle in a way. (i.e. return a + b;)
  *  Array - this is a group of items that are shown in a list type set. It can be comprised of any kind of items. Items can be called down by number, each item is given an integer starting with 0 and going up. It it represented with square brackets. 
  ````var arr = ["Item one", 2, true]````
  * Array.Push - the .push at the end of the array will take a new element to add into the array and add it to the end. It will also provide a new total length of the given array. 
 ````
 var fruit = ["banana", "orange"];
 var fruitTotal = fruit.push ("strawberry")
 console.log(fruit) // banana, orange, strawberry
````
  * Array.pop - the .pop will remove the last item within the array, from the array. 
````
 var arr = [1, 2, 3]
 var popped = arr.pop 
 console.log(popped)
// 1, 2
````
  *  Function - This is a way to save bits of code and assign values within the perameters given. This can help us to build working systems that complete certain tasks, depending on what objects the task is given. 

````
function subtraction (a,b){a-b;}subtraction(x,y);
````
  
