----------------------------
React Hooks and Custom Hooks
----------------------------




* Getting started with hooks *

1) - Working with React hooks
Hooks can actually simplify your applications greatly and introduce performance gains that can make your code more readable and easier to manage, as well as your code more shareable and reusable. 

2) - useState hook
which is used to work with state in a react component with state being all the data and app is working with at a given time. react uses the array data structure for the used state hooks return value. It returns an array with two values: the current state and a function to update it. The Hook takes an initial state value as an argument and returns an updated state value whenever the setter function is called.

3) - pure and impure functions
Pure functions return the same output if we use the same input parameters. However, impure functions give different outcomes when we pass the same arguments multiple times. Pure functions always return some results. Impure functions can execute without producing anything.

4) - Side Effects
Data fetching, setting up a subscription, and manually changing the DOM in React components are all examples of side effects. Whether or not you're used to calling these operations “side effects” (or just “effects”), you've likely performed them in your components before.

5) - useEffect hook
The useEffect Hook allows you to perform side effects in your components. It tell React that your component needs to do something after render. React will remember the function you passed (we'll refer to it as our “effect”), and call it later after performing the DOM updates. It's use for eliminate the side effects of using class-based components.




* Rules of Hooks and Fetching Data with Hooks *

6) - rules of hooks
The four main rules of hooks are as follows. 
1 - you should only call hooks from a React component function.
2 - you should only call hooks at the top level of a React component function.
3 - you are allowed to call multiple state hooks or effect hooks inside a component.
4 - always make these multiple hook calls in the same sequence. 

7) - Fetch function
Fetch is used to make a server requests to retrieve some JSON data from it. Fetch API is a set of functionalities that we have at our disposal to use in JavaScript to make such a server request. and we can fetch data using hooks too.

8) - APIs
An API call in React refers to making a request to a web API from a React application. React uses API calls to connect with external services to receive or send data. They allow your React application to interact with other systems and exchange information with them.
The Fetch API provides a JavaScript interface for accessing and manipulating parts of the protocol, such as requests and responses. 




* Advanced hooks *

9) - What is useReducer and how it differs from useState
