Instructions:

- Add your answers inline to the markdown file.
- Use your own words.
- Come up with an answer from memory. Write it down, even if the answer is "I don't know."
- Then, we will go over the answers in class. Write down your revised answer below your original answer.

---
### Part 1: Control Flow - 15 minutes

1. Draw a diagram of an if statement. Name each of the components and how they work together.

if (something === true) {
  // do something;
};


2. Draw a diagram of a for loop. Describe each of its components. Indicate the order in which they are executed / evaluated.

for (starting point; end condition; steps taken) {
  // do something;
};

3. Functions
 - 3a. Draw a diagram of a function. Describe each of its components and what each component does. Specify which of them are optional.

 var something = function(parameter) {  // parameter is optional
   // what the function does
   // returns something                 // return is optional
 }

 - 3b. Draw a diagram of a function being called, showing the instruction execution order.

functionName(parameter);

### Part 2: Data Types - 10 minutes

4. Primitive Data Types
 - 4a. Give an example of an empty string and a non-empty string.

empty string: ''
non-empty string: 'string'

 - 4b. Give an example of a boolean.

true or false

 - 4c. Give an example of a Number.

23235234

5. Arrays
 - 5a. Give an example of an empty array.

var array = []

 - 5b. Give an example of an array with three elements in it.

var array = [1, 2, 3]

 - 5c. How do you add another element to this array?

array.push(value);

 - 5d. How do you get the length of this array?

array.length;

 - 5e. Show how to iterate through the array using a loop.

for (i = 0; i = array.length; i++) {
  console.log(i);
}

6. Objects
 - 6e. Give an example of an empty object.

object = {};

 - 6b. Give an example of an object with three keys and three values.

object = {
  'key1',
  'key2',
  'key3',
  1,
  2,
  3
};

 - 6c. Give an example of an object with two keys and two functions as values.

 object = {
   'key1',
   'key2',
   1,
   2
 };

 - 6d. Describe one way of adding a key to an object.

object.key = 'something'

 - 6e. Describe the other way of adding a key to an object



 - 6f. Explain the difference between these two ways, and when it is appropriate to use each way.



 - 6g. Describe how to iterate though an object using a loop.



---
### Part 3: Algorithms - 20 minutes

7. What is an algorithm?

A description for a computer to execute something.

8. For the following problem, first write down how exactly to solve the problem in English. Once you are able to describe it in English, translate it into code.

```js
// Given an array of values, write a function that finds the index of where the value is located, and if nothing is found, returns -1.
// Do not use the indexOf function.
// example: for ['apple', 'orange', 'pineapple']
	// 'orange' returns '1'
	// 'durian' returns '-1'
```



9. Again, for the following problem, first write down how exactly to solve the problem in English. Once you are able to describe it in English, translate it into code.

```js
// Write a function that finds all the indexes of where the value is located and returns them in an array, and if nothing is found, returns -1
// example: ['apple', 'orange', 'orange', 'pineapple']
	// 'orange' returns [1,2]
```

var array = ['apple', 'orange', 'orange', 'pineapple'];

function findIndex(parameter) {
  var foundIndex = -1;
  for (var i = 0; i < array.length; i++) {
    if ((array[i]) === parameter) {
      foundIndex = i;
    } console.log([foundIndex]);
  }
  return foundIndex;
}
