Watch this video to understand what to do in this exercise block [link](https://www.youtube.com/watch?v=zGpplZj4zY0&feature=youtu.be)

## Getting To Know Array Methods

Go to this [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) and look for the name of method to learn about it.

**Write in your own way of understanding (don't copy paste)**

Only if you are done with step 1 you should go ahead.

1. Practice it by yourself in console (2-3 times to understand)
2. Data types of parameters
3. Return value type
4. Write three examples
5. In your words what this method does.
6. Does it mutate the original value or not (check https://doesitmutate.xyz)

Example:

1. `concat`

   - Parameter: n (any) number of values (number, string, boolean, array, null, undefined, object and function etc)
   - Return: a single Array consisting of by all the values passed as parameters in the same order.
   - Example:
     ```js
     let numbers = [1, 2, 3];
     numbers.concat(4); //[1,2,3,4]
     let sentanceArray = 'A quick brown fox jumped over a lazy'.split(' ');
     sentanceArray.concat('dog').join(' '); //"A quick brown fox jumped over a lazy dog"
     let colors = ['red', 'green', 'blue'];
     colors.concat('black', 'red', 21, true); // ['red','green','blue','black', 'red', 21, true]
     ```
   - `concat` accepts n number of values and returns one array with all the values in same order. It does not change the original array.
   - No it does not mutate the original array

2. `join`

   - Parameter: Specifies a string to separate each pair of adjacent elements of the array. The separator is converted to a string if necessary. If omitted, the array elements are separated with a comma (","). If separator is an empty string, all elements are joined without any characters in between them.
   - Return: A string with all array elements joined. If arr.length is 0, the empty string is returned.
   - Example:
     ```js
     let numbers = [1, 2, 3];
     numbers.join(); //'1,2,3'
     let elements = ['Fire', 'Air', 'Water'];
     elements.join(); // 'Fire,Air,Water'
     elements.join(''); // 'FireAirWater'
    elements.join('-'); // 'Fire-Air-Water'
     ```
   - `join` The string conversions of all array elements are joined into one string.
   - No it does not mutate the original array

3. `flat`
 - Parameter: depth Optional
The depth level specifying how deep a nested array structure should be flattened. Defaults to 1.
   - Return: A new array with the sub-array elements concatenated into it.
   - Example:
     ```js
     let num1 = [1, 2, 3, [4, 5]];
     num1.flat(); // [1, 2, 3, 4, 5]
     let num2 = [1, 2, 3, [4, 5, [6, 7]]];
     num2.flat(); // [1, 2, 3, 4, 5, [6, 7]]
     let num3 = [1, 2, 3, [4, 5, [6, 7]]];
     num3.flat(2); // [1, 2, 3, 4, 5, 6, 7]
     ```
   - `flat` TThe flat() method creates a new array with all sub-array elements concatenated into it recursively up to the specified depth.
   - No it does not mutate the original array
4. `push`
 - Parameter: The element(s) to add to the end of the array.
   - Return: The new length property of the object upon which the method was called.
   - Example:
     ```js
     let animals = ['pigs', 'goats', 'sheep'];
     let count = animals.push('cows');
     console.log(count); // 4
     ```
   - `push` The push() method adds one or more elements to the end of an array and returns the new length of the array.
   - yes it does mutate the original array
5. `indexOf`
6. `lastIndexOf`
7. `includes`
8. `reverse`
9. `every`
10. `shift`
11. `splice`
12. `find`
13. `unshift`
14. `findIndex`
15. `filter`
16. `flat`
17. `forEach`
18. `map`
19. `pop`
20. `reduce`
21. `slice`
22. `some`
