# methods-practice
Give a short description of what the method does, how it works, it's time complexity, and give three examples of it in action!

# Array Methods:

# map 
The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.
Time complexity
Therefore, the function loops through every object in the array, having a complexity of O(n)

const array1 = [1, 4, 9, 16];

// pass a function to map
const map1 = array1.map(x => x * 2);

console.log(map1);
// expected output: Array [2, 8, 18, 32]



# reduce
The reduce() method executes a reducer function (that you provide) on each element of the array, resulting in a single output value.
Time complexity
Therefore, the function loops through every object in the array, having a complexity of O(n)

const array1 = [1, 2, 3, 4];
const reducer = (accumulator, currentValue) => accumulator + currentValue;

// 1 + 2 + 3 + 4
console.log(array1.reduce(reducer));
// expected output: 10

// 5 + 1 + 2 + 3 + 4
console.log(array1.reduce(reducer, 5));
// expected output: 15






# filter
The filter() method creates a new array with all elements that pass the test implemented by the provided function.
Time complexity
Therefore, the function loops through every object in the array, having a complexity of O(n)

const words = ['spray', 'limit', 'elite', 'exuberant', 'destruction', 'present'];

const result = words.filter(word => word.length > 6);

console.log(result);
// expected output: Array ["exuberant", "destruction", "present"]


# forEach
The forEach() method executes a provided function once for each array element.
Time complexity
Therefore, the function loops through every object in the array, having a complexity of O(n)
const array1 = ['a', 'b', 'c'];

array1.forEach(element => console.log(element));

// expected output: "a"
// expected output: "b"
// expected output: "c"

# sort
The sort() method sorts the elements of an array in place and returns the sorted array. The default sort order is ascending, built upon converting the elements into strings, then comparing their sequences of UTF-16 code units values.
const months = ['March', 'Jan', 'Feb', 'Dec'];
months.sort();
console.log(months);
// expected output: Array ["Dec", "Feb", "Jan", "March"]

const array1 = [1, 30, 4, 21, 100000];
array1.sort();
console.log(array1);
// expected output: Array [1, 100000, 21, 30, 4]

# slice
The slice() method returns a shallow copy of a portion of an array into a new array object selected from start to end (end not included) where start and end represent the index of items in that array. The original array will not be modified.
Time complexity
Therefore, the function loops through every object in the array, having a complexity of O(n)

# pop
The pop() method removes the last element from an array and returns that element. This method changes the length of the array.

# shift
The shift() method removes the first element from an array and returns that removed element. This method changes the length of the array.

# push
The push() method adds one or more elements to the end of an array and returns the new length of the array.


# unshift
The unshift() method adds one or more elements to the beginning of an array and returns the new length of the array.

# includes
The includes() method determines whether an array includes a certain value among its entries, returning true or false as appropriate.

# indexOf
The indexOf() method returns the first index at which a given element can be found in the array, or -1 if it is not present.

# every
The every() method tests whether all elements in the array pass the test implemented by the provided function. It returns a Boolean value.


































# String Methods:

# charAt
The String object's charAt() method returns a new string consisting of the single UTF-16 code unit located at the specified offset into the string.

# charCodeAt
The charCodeAt() method returns an integer between 0 and 65535 representing the UTF-16 code unit at the given index.


# concat
The concat() method concatenates the string arguments to the calling string and returns a new string.

# includes
The includes() method performs a case-sensitive search to determine whether one string may be found within another string, returning true or false as appropriate.

# indexOf
The indexOf() method returns the index within the calling String object of the first occurrence of the specified value, starting the search at fromIndex. Returns -1 if the value is not found.

# match
The match() method retrieves the result of matching a string against a regular expression.

# repeat
The repeat() method constructs and returns a new string which contains the specified number of copies of the string on which it was called, concatenated together.




# replace
The replace() method returns a new string with some or all matches of a pattern replaced by a replacement. The pattern can be a string or a RegExp, and the replacement can be a string or a function to be called for each match. If pattern is a string, only the first occurrence will be replaced.
search
The search() method executes a search for a match between a regular expression and this String object.

# slice
The slice() method extracts a section of a string and returns it as a new string, without modifying the original string.

# split
The split() method divides a String into an ordered list of substrings, puts these substrings into an array, and returns the array.  The division is done by searching for a pattern; where the pattern is provided as the first parameter in the method's call.




# substr 
The substr() method returns a portion of the string, starting at the specified index and extending for a given number of characters afterwards.

# toLowerCase
The toLowerCase() method returns the calling string value converted to lowercase.
Time complexity
Therefore, the function loops through every object in the array, having a complexity of O(n)

# toUpperCase
The toUpperCase() method returns the calling string value converted to uppercase (the value will be converted to a string if it isn't one).


# trim
The trim() method removes whitespace from both ends of a string. Whitespace in this context is all the whitespace characters (space, tab, no-break space, etc.) and all the line terminator characters (LF, CR, etc.).

