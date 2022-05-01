Watch this video to understand what to do in this exercise block [link](https://www.youtube.com/watch?v=zGpplZj4zY0&feature=youtu.be)

#### Getting To Know String Methods

Go to this [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) and look for the name of method to learn about it.

**Write in your own way of understanding (don't copy paste)**

Only if you are done with step 1 you should go ahead.

1. Practice it by yourself in console (4-5 times to understand)
2. Data types of parameters
3. Return value type
4. Write three examples
5. In your own words and one sentence explain what this method does.

Example:

1. `charAt`

   - Parameter: (index) defaults to 0 - (number data type)
   - Return: character at specific index in the string (string data type)
   - Example:
     ```js
     let name = 'Arya Stark';
     name.charAt(2); //"y"
     let sentance = 'A quick brown fox jumped over a lazy dog';
     sentance(4); // "i"
     let houseName = 'Starks';
     houseName.charAt(0); // "S"
     ```
   - `charAt` accepts a index (number data type) and return the character on that index in the string.

2. `toUpperCase`
   - Return: A new string representing the calling string converted to upper case.
   - Example:
     ```js
     const sentence = 'The quick brown fox jumps over the lazy dog.';
     sentence.toUpperCase() // "THE QUICK BROWN FOX JUMPS OVER THE LAZY DOG."
     let name = 'Arya Stark';
     name.toUpperCase(); //"ARYA STARK"
     let houseName = 'Starks';
     houseName.toUpperCase(); // "ARYA STARK"
     ```

3. `toLowerCase`
  -Return: A new string representing the calling string converted to lower case.
   - Example:
     ```js
     const sentence = 'The quick brown fox jumps over the lazy dog.';
     sentence.toLowerCase() // 'the quick brown fox jumps over the lazy dog.'
     let name = 'Arya Stark';
     name.toLowerCase(); //'arya stark'
     let houseName = 'Starks';
     houseName.toLowerCase(); //'arya stark'
     ```

4. `trim`
    -Return: A new string representing str stripped of whitespace from both its beginning and end.
    -Examples:
     ```js
     const greeting = '   Hello world!   ';
     greeting.trim(); // 'Hello world!'
     ```

5. `trimEnd`
  -Return: A new string representing str stripped of whitespace from its end (right side).
  -Examples:
    ```js
     const greeting = '   Hello world!   ';
     greeting.trimEnd(); // '   Hello world!'
     ```
6. `trimStart`
-Return: A new string representing str stripped of whitespace from its beginning (left side).
-Examples:
     ```js
     const greeting = '   Hello world!   ';
     greeting.trimStart(); // 'Hello world!   '
     ```

7. `concat`
   - Parameter: Arrays and/or values to concatenate into a new array. If all valueN parameters are omitted, concat returns a shallow copy of the existing array on which it is called. See the description below for more details.
   - Return: A new Array instance.
   - Example:
     ```js
    const array1 = ['a', 'b', 'c'];
    const array2 = ['d', 'e', 'f'];
    const array3 = array1.concat(array2); // ['a', 'b', 'c', 'd', 'e', 'f']
    ```
8. `endsWith`
- Parameter: searchString
             The characters to be searched for at the end of str.
   - Return: true if the given characters are found at the end of the string; otherwise, false.
   - Example:
     ```js
     let str = 'To be, or not to be, that is the question.'
     str.endsWith('question.'); // true
     str.endsWith('to be'); // false
     ```
9. `includes`
- Parameter: searchElement
               The value to search for.
   - Return: A boolean value which is true if the value searchElement is found within the array (or the part of the array indicated by the index fromIndex, if specified).

   Values of zero are all considered to be equal, regardless of sign. (That is, -0 is considered to be equal to both 0 and +0), but false is not considered to be the same as 0.


   - Example:
     ```js
    const array1 = [1, 2, 3];

    array1.includes(2); // true

    const pets = ['cat', 'dog', 'bat'];

    pets.includes('cat'); // true
   
    pets.includes('at'); // false
    ```
10. `indexOf`
- Parameter: searchElement
             Element to locate in the array.
   - Return: The first index of the element in the array; -1 if not found.
   - Example:
     ```js
     const array = [2, 9, 9];
     array.indexOf(2);     // 0
     array.indexOf(7);     // -1
     array.indexOf(9, 2);  // 2
     array.indexOf(2, -1); // -1
     array.indexOf(2, -3); // 0
     ```
11. `lastIndexOf`
12. `padEnd`
13. `padStart`
14. `repeat`
15. `replace`
16. `slice`
17. `split`
18. `substring`
