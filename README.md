# Programming Foundations Lesson 2.2: Arrays

## Exercise 1

Make an array with the first 10 Fibonacci numbers: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34

a) What is the value of the seventh Fibonacci number? Console log out the answer.

b) Make a varaible sum. Use a for loop to go over the array, and add up the value of the numbers. Console log out the sum.

## Exercise 2

Given the Array:

```js
let myNumbers = [13, -2, 18, 4, 42, 12, 9, -21, -3];
```

a) Console log out how many items the Array holds.

b) Remove the last item in the Array.

c) Add the number 14 to the end of the Array.

d) Add the number 3 to the start of the Array.

e) Use a for loop to go over the Array and find the largest number.

> Tip: Use a variable largest and compare every item to the largest, update largest if the item is larger.

## Exercise 3

Given the Array: 

```js
let vegetables = ['Cabbage', 'Turnip', 'Radish', 'Carrot'];
```

a) Console log out how many items the Array holds.

b) Add "Tomato" to the end of the Array.

c) Add "Cucumber" to the start of the Array.

d) Use a for loop to go over the Array, and for each item, console log out the value of the item and how many letters it contains (eg. "Tomato contains 6 letter").

## Exercise 4

Given the array:

```js
let mixed = ["Dill", 42, true, , 13, "13", null];
```

a) Make a for loop to loop over all items and, for each item console log out the index, value and data type of the element.

b) Add the string "Hello, World!" to the undefined element in the Array `mixed`, then console.log out `mixed`.

c) Make another for loop and add up all the items in the Array that has a numeric data type. Console log the sum.

## Exercise 5

Given the two Arrays:

```js
let vegetables = ['Cabbage', 'Turnip', 'Radish', 'Carrot'];
let fruits = ["Banana", "Orange", "Lemon", "Apple", "Mango"];
```

a) Merge the 2 Arrays into a new Array, `greeneries`.

b) Sort the merged Array then console log it.

> Tip: Look at the `Array.sort()` method.

c) Console log out the first element in the merged, then sorted Array.

d) Console log out the last element in the merged, then sorted Array.

e) Sort the merged Array in reverse order.

> Tip: Look at the `Array.reverse()`, and remember to `sort()` it first.

## Exercise 6 - Level 2

Given the Array of numbers from Exercise 2

```js
let myNumbers = [13, -2, 18, 4, 42, 12, 9, -21, -3];
```

a) Sort `myNumbers` using the Array.sort() method from above. Console log the sorted menu. Did you get the result you expected?

b) Use a *compare function* to sort the numbers by numeric value, rather then alphabetically.

c) Sort the numbers in reverse order, ie. largest first, by adjusting the compare function.
