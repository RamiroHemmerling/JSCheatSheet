# JavaScript Array Methods Cheat Sheet


## 1. forEach()
Description: Executes a function for each element in the array.
```js
const arr = [1, 2, 3];
arr.forEach(num => console.log(num));
```
- Output: 1 2 3

## 2. map()
Description: Creates a new array with the results of calling a function on every element in the array.
```js
const doubled = arr.map(num => num * 2);
console.log(doubled);
```
- Output: [2, 4, 6]

## 3. filter()
Description: Creates a new array with all elements that pass the test implemented by the provided function.
```js
const even = arr.filter(num => num % 2 === 0);
console.log(even);
```
- Output: [2, 4]

## 4. reduce()
Description: Reduces the array to a single value by executing a reducer function on each element.
```js
const sum = arr.reduce((acc, num) => acc + num, 0);
console.log(sum);
```
- Output: 10

## 5. find()
Description: Returns the first element that satisfies the provided testing function.
```js
const found = arr.find(num => num > 2);
console.log(found);
```
- Output: 3

## 6. some()
Description: Tests whether at least one element in the array passes the implemented test. Returns true or false.
```js
const hasEven = arr.some(num => num % 2 === 0);
console.log(hasEven);
```
- Output: true

## 7. every()
Description: Tests whether all elements in the array pass the implemented test. Returns true or false.
```js
const allEven = arr.every(num => num % 2 === 0);
console.log(allEven);
```
- Output: false

## 8. includes()
Description: Checks if an array contains a specified element. Returns true or false.
```js
const containsTwo = arr.includes(2);
console.log(containsTwo);
```
- Output: true

## 9. concat()
Description: Merges two or more arrays and returns a new array.
```js
const arr1 = [1, 2];
const arr2 = [3, 4];
const combined = arr1.concat(arr2);
console.log(combined);
```
- Output: [1, 2, 3, 4]

## 10. slice()
Description: Returns a shallow copy of a portion of an array into a new array based on start and end indexes.
```js
const sliced = arr.slice(1, 3);
console.log(sliced);
```
- Output: [2, 3]

## 11. splice()
Description: Changes the contents of an array by removing, replacing, or adding elements.
```js
arr.splice(2, 1, 99);
console.log(arr);
```
- Output: [1, 2, 99, 4]

## 12. sort()
Description: Sorts the elements of an array in place and returns the sorted array.
```js
const unsortedArr = [3, 1, 4, 2];
unsortedArr.sort();
console.log(unsortedArr);
```
- Output: [1, 2, 3, 4]

## 13. reverse()
Description: Reverses the order of the elements in the array in place.
```js
unsortedArr.reverse();
console.log(unsortedArr);
```
- Output: [4, 3, 2, 1]

