# HW6_String._Methods_of_string 

# JS STRING. STRING METHODS

## What is a Method in Javascript?

A method is a block of code which only runs when it is called.
You can pass data, known as parameters, into a method.
Methods are used to perform certain actions, and they are
also known as functions.

# String in Javascript
## Create string in Javascript

We've three types of making string
1. Double quotes
2. Single quotes
3. Backticks

1) Double quotes. 

<h2 style="color:red;">Example:</h2>

```js
console.log("Hello");
```

2) Single quotes. 

<h2 style="color:red;">Example:</h2>

```js
console.log('Hello');
```

3) Backticks

<h2 style="color:red;">Example:</h2>

```js
console.log(`Hello${variable}`);
```

How we see single quotes with double quotes are the same, but the backticks is different than them. Because in the string type of backticks we can add the variables in the signs ${} inside backticks.

So for using the string we need to know about methods of string.

So let's start from here...

# JAVA SCRIPT STRING METHODS

In js we've many types of the methods of strings, but the main methods are this:
```js
1. ➢ charAt()
2. ➢ slice()
3. ➢ concat()
4. ➢ trim()
5. ➢ substring()
6. ➢ includes() 
7. ➢ split()
8. ➢ indexOf()
9. ➢ replace() 
10. ➢ toString()
11. ➢ replaceAll() 
12. ➢ toLowerCase()
13. ➢ repeat() 
14. ➢ toUpperCase()
```
## JavaScript String method charAt()

The <span style="color:red;">charAt()</span> method returns the character at a specified index (position) in a string.
The index of the first character is 0, the second 1, ...
The index of the last character is string length - 1 .

<h2 style="color:red;">Example:</h2>

Get the first character in a string:

```js
let text = "Hello world!";
let firstLetter = text.chatAt(0);
console.log(firstLetter);
```

<h2 style="color:red;">Output:</h2>

```js
H
```

<h2 style="color:red;">Example:</h2>

Get the second character in a string:

```js
let text = "Hello world!";
let secondLetter = text.chatAt(1);
console.log(secondLetter);
```

<h2 style="color:red;">Output:</h2>

```js
e
```

<h2 style="color:red;">Example:</h2>

Get the last character in a string:

```js
let text = "Hello world!";
let lastLetter = text.chatAt(1);
console.log(lastLetter);
```

<h2 style="color:red;">Output:</h2>

```js
!
```

## JavaScript String method concat()

The <span style="color:red;">concat()</span> method joins two or more strings.
The <span style="color:red;">concat()</span> method does not change the existing strings.
The <span style="color:red;">concat()</span> method returns a new string.

<h2 style="color:red;">Example:</h2>

Join two strings:

```js
const text1 = "Hello ";
const text2 = "world!";
console.log(text1.concat(text2));
```

<h2 style="color:red;">Output:</h2>

```js
Hello world!
```

## JavaScript String method replace()

The <span style="color:red;">replace()</span> method searches a string for a value or a regular expression.
The <span style="color:red;">replace()</span> method returns a new string with the value(s) replaced.
The <span style="color:red;">replace()</span> method does not change the original string

<h2 style="color:red;">Example:</h2>

Replace Windows:

```js
let text = "Windows - is one type of operation system";
let replace = text.replace("Windows", "Linux");
```

<h2 style="color:red;">Output:</h2>

```js
Linux - is one type of operation system
```

## JavaScript String method replaceAll()

The <span style="color:red;">replaceAll()</span> method returns a new string with all matches of a pattern replaced by
a replacement.

<h2 style="color:red;">Example:</h2>

```js
const p = "Hello my best friend";
let result = p.replaceAll('friend', 'enemy');
console.log(result);
```

<h2 style="color:red;">Output:</h2>

```js
Hello my best enemy
```

## JavaScript String method split()

The <span style="color:red;">split()</span> method splits a string into an array of substrings. The <span style="color:red;">split()</span> method returns the new
array. The <span style="color:red;">split()</span> method does not change the original string. If (" ") is used as separator, the string
is split between words.

<h2 style="color:red;">Example:</h2>

```js
const text = "Hello";
let text2 = text.split("");
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
[ 'H', 'e', 'l', 'l', 'o' ]
```

## JavaScript String method substring(start,end)

The <span style="color:red;">substring()</span> method extracts characters, between two indices (positions), from a string, and
returns the substring.
The <span style="color:red;">substring()</span> method extracts characters from start to end (exclusive).
The <span style="color:red;">substring()</span> method does not change the original string.
If start is greater than end, arguments are swapped: (4, 1) = (1, 4).
Start or end values less than 0, are treated as 0.

<h2 style="color:red;">Example:</h2>

```js
const text = "Hello world!";
let text2 = text.substring(3, 7);
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
lo w
```

Notice: It can't work, when you want to start the index of -1, -2, ..., -n;

<h2 style="color:red;">Example:</h2>

```js
const text = "Hello world!";
let text2 = text.substring(-2);
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
Hello world!
```

## JavaScript String method slice(start, end)

The <span style="color:red;">slice()</span> method returns a shallow copy of a portion of an array into a new array object
selected from start to end ( end not included) where start and end represent the index of items
in that array.

```js
const text = "Hello world!";
let text2 = text.slice(3, 7);
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
lo w
```

## JavaScript String method toLowerCase()

The <span style="color:red;">toLowerCase()</span> method converts a string to lowercase letters.
The <span style="color:red;">toLowerCase()</span> method does not change the original string.

<h2 style="color:red;">Example:</h2>

```js
const text = "Hello World!";
let text2 = text.toLowerCase();
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
hello world!
```

## JavaScript String method toUpperCase()

The <span style="color:red;">toUpperCase()</span> method converts a string to uppercase letters.
The <span style="color:red;">toUpperCase()</span> method does not change the original string.

<h2 style="color:red;">Example:</h2>

```js
const text = "Hello World!";
let text2 = text.toUpperCase();
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
HELLO WORLD!
```

## JavaScript String method trim()

Method <span style="color:red;">trim()</span> removes whitespace from both sides of a string.
The <span style="color:red;">trim()</span> method does not change the original string.

<h2 style="color:red;">Example:</h2>

```js
const text = "    Hello world!    ";
let text2 = text.toUpperCase();
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
Hello world!
```

## JavaScript String method includes()

The <span style="color:red;">includes()</span> method returns <span style="color:red;">true</span> if a string contains a specified string.
Otherwise it returns <span style="color:red;">false</span>.
The <span style="color:red;">includes()</span> method is case sensitive.

<h2 style="color:red;">Example:</h2>

```js
const text = "Hello world!";
let text2 = text.includes("world");
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
true
```

## JavaScript String method toString()

The toString() method returns a string representing the object.
By default toString() takes no parameters.

<h2 style="color:red;">Example:</h2>

```js
const num = 100;
let toText = text.toString();
console.log(typeof(toText));
```

<h2 style="color:red;">Output:</h2>

```js
string
```

## JavaScript String method indexOf()

The indexOf() method returns the position of the first occurrence of a value in a string.
The indexOf() method returns -1 if the value is not found.
The indexOf() method is case sensitive.

<h2 style="color:red;">Example:</h2>

```js
const text = "Hello World!";
let text2 = text.indexOf("World!");
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
1
```

## JavaScript String method repeat()

The repeat() method creates a new string by repeating the given string a specified number of
times and returns it.

<h2 style="color:red;">Example:</h2>

```js
const text = "Hello";
let text2 = text.repeat(3);
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
HelloHelloHello
```
## JavaScript String method at()

The at() method takes an integer value and returns a new String.
This method allows for positive and negative integers. Negative integers count
back from the last string character.

<h2 style="color:red;">Example:</h2>

```js
const text = "Hello";
let text2 = text.at(3);
console.log(text2);
```

<h2 style="color:red;">Output:</h2>

```js
l
```

# JavaScript Number methods

In js we've many types of the methods of number methods like strings, but the main methods are this:



## JavaScript Number methods Math.round(),ceil(),floor()

The Math.floor() function rounds down a number to the next smallest integer

<h2 style="color:red;">Example:</h2>

```js
let num = 3.9;
let res = Math.floor(num);
```

<h2 style="color:red;">Output:</h2>

```js
3
```