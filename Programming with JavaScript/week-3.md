---------------------
Programming Paradigms
---------------------




* Introduction to Functional Programming *

1) -  Functional Programming
functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions. It emphasizes the use of pure functions, immutability, and higher-order functions to create programs that are more predictable and easier to reason about.

2) - Function calling and Recursion
A function call is an expression containing the function name followed by the function call operator, () . 
Recursion is a process of calling itself. A function that calls itself is called a recursive function. 

3) - Scope
Scope is all about code accessibility. It determines which parts of the code are accessible and which parts are inaccessible. You may recall that all the code outside of functions is referred to as global scope, and all the code inside of a function is known as local scope.

4) - Scoping with var, let and const
let and const - variables with let or const, they become immediately scoped to the code block they were created in. With a let or a const variable, you cannot use it in your code before you declare it. 
var - you can use it in your code even before it is declared. Also, you can redeclare the same variable when you use VAR. 




* Introduction to Object-Oriented Programming *

5) - OOP
OOP revolves around the idea of organizing our programs using objects to group related data and functionality. This is in contrast to the functional programming approach, where the data used in the app needs to be kept separate from functions that operate on that data. With the OOP approach, you create an object and store all data related to that object including variables, functions and output statements. ou may recall that functions inside objects are known as methods. An advantage to using the OoP approach is that you can build as many objects as you need.

6) - Classes
They are essentially a blueprint that you can repeatedly use to build new objects of a certain kind, as many times as you like.

7) - Constructor
It is a special function that creates and initializes an object instance of a class. In JavaScript, a constructor gets called when an object is created using the new keyword. The purpose of a constructor is to create a new object and set values for any existing object properties.

8) - Inheritance
It refers to passing down characteristics from a parent to a child so that a new piece of code can reuse and build upon the features of an existing one. JavaScript implements inheritance by using objects.




* Advanced JavaScript Features *

9) - De-structuring arrays and objects
It is a useful JavaScript feature to extract properties from objects and bind them to variables. Even better, object destructuring can extract multiple properties in a single statement, can access properties from nested objects, and can set a default value if the property doesn't exist.

10) - For- of loops and objects
when you run on objects in JavaScript for in loops, iterate over the properties of the object and its prototype. While for of loops do this only for the objects' properties.

11) - Template literals
Template literals are an alternative way of working with strings, this are literals delimited with backtick ( ` ) characters, allowing for multi-line strings, string interpolation with embedded expressions, and special constructs called tagged templates.

12) - Data Structure
A data structure is a way to organize data. JavaScript's most common data structures such as, objects, arrays, maps and sets.
objects - It is noniterable collection of key value pairs and you use objects when you need to store and later access a value under a key.
arrays - It is an ordered iterable collection of values. you use arrays when you need to store and later access a value under an index.  
maps - which is like an array because it's iterable. However, it consists of key value pairs. It's important not to confuse a map with an 
       object. With maps any value can be used as a key. With objects, keys can only be strings or symbols.
sets - This is another collection where each item in the collection must be unique.

13) - Spread operator
This is a method to copy the properties of an object onto a newly created object. It can spread out array items and join objects together.

14) - Rest operator
It allows a function to take an indefinite number of arguments and bundle them in an array, thus allowing us to write functions that can accept a variable number of arguments, irrespective of the number of parameters defined.




* JavaScript in the Browser * 

15) - JavaScript modules
JavaScript modules are standalone units of code that you can reuse again and again. Being standalone means that you can add them to your program, remove them and replace them with other modules.

16) - JavaScript DOM manipulation
It allows you to change properties of objects on a webpage. also it allows developers to interact with and modify the structure, style, and content of web pages. The DOM is the model of the HTML file saved as a JavaScript object in your browser's memory. The browser automatically builds the DOM for every webpage that it downloads. 

17) - JavaScript selectors
It can be used to select elements in the DOM. It can be an element ID, class, or tag name such as document. querySelector('my-id') . 

18) - Event handling
In JavaScript, the function that handles captured events is known as the event handler. 

19) - JavaScript Object Notation - JSON
JSON is basically just an object represented in the form of a string. It has some specific formatting but it's a string nonetheless. So to work with JSON, it is common to convert it back to a JavaScript object to work with its properties and methods. 