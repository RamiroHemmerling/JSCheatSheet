# JavaScript Array Methods Cheat Sheet

```js
// 1. forEach()
// Executes a function for each element in the array.
const arr = [1, 2, 3];
arr.forEach(num => console.log(num));
// Output: 1 2 3

// 2. map()
// Creates a new array with the results of calling a function on every element in the array.
const doubled = arr.map(num => num * 2);
console.log(doubled); 
// Output: [2, 4, 6]

// 3. filter()
// Creates a new array with all elements that pass the test implemented by the provided function.
const even = arr.filter(num => num % 2 === 0);
console.log(even); 
// Output: [2, 4]

// 4. reduce()
// Reduces the array to a single value by executing a reducer function on each element.
const sum = arr.reduce((acc, num) => acc + num, 0);
console.log(sum);
// Output: 10

// 5. find()
// Returns the first element that satisfies the provided testing function.
const found = arr.find(num => num > 2);
console.log(found); 
// Output: 3

// 6. some()
// Tests whether at least one element in the array passes the implemented test. Returns true or false.
const hasEven = arr.some(num => num % 2 === 0);
console.log(hasEven); 
// Output: true

// 7. every()
// Tests whether all elements in the array pass the implemented test. Returns true or false.
const allEven = arr.every(num => num % 2 === 0);
console.log(allEven); 
// Output: false

// 8. includes()
// Checks if an array contains a specified element. Returns true or false.
const containsTwo = arr.includes(2);
console.log(containsTwo); 
// Output: true

// 9. concat()
// Merges two or more arrays and returns a new array.
const arr1 = [1, 2];
const arr2 = [3, 4];
const combined = arr1.concat(arr2);
console.log(combined); 
// Output: [1, 2, 3, 4]

// 10. slice()
// Returns a shallow copy of a portion of an array into a new array based on start and end indexes.
const sliced = arr.slice(1, 3);
console.log(sliced); 
// Output: [2, 3]

// 11. splice()
// Changes the contents of an array by removing, replacing, or adding elements.
arr.splice(2, 1, 99);
console.log(arr); 
// Output: [1, 2, 99, 4]

// 12. sort()
// Sorts the elements of an array in place and returns the sorted array.
const unsortedArr = [3, 1, 4, 2];
unsortedArr.sort();
console.log(unsortedArr); 
// Output: [1, 2, 3, 4]

 13. reverse()
// Reverses the order of the elements in the array in place.
unsortedArr.reverse();
console.log(unsortedArr); 
// Output: [4, 3, 2, 1]
```
