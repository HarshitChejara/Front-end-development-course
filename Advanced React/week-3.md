---------------
JSX and testing
---------------




* JSX Deep Dive *

1) - JSX, Components and Elements
JSX - It is syntax extension to JavaScript that React uses to describe what the UI should look like. However,even though JSX looks like HTML

component - it's essentially a more powerful abstraction that combines both markup and business logic into an entity called a component.  

element - It is just a way to represent the final HTML output as a plain object. It consists primarily of two attributes, type and props. 
         Type defines the type of node such as a button and props encompasses all the properties the component receives in a single object.

2) - Component composition with children
There are two main features that enable component composition; containment and specialization. 
Containment - It refers to the fact that some components don't know their children ahead of time. This is especially common for components 
              like a sidebar or a dialog, where they delimit a specific area in your UI to contain other elements.         
specialization - Specialization defines components as being special cases of other components. which uses the dialog component and renders 
                 as children a title and a description.     

3) - React.cloneElement and react.children
These react APIs used to manipulate the Render Output dynamically.            
React.cloneElement - This is part of the react top-level API and it's used to manipulate and transform elements. Top-level API refers to 
                     the way you would import those functions from the react package. You can either import react as a global object and the top of your file and access them as methods on that object. React.cloneElement effectively clones and returns a new copy of a provided element. The first argument is the react element you would like to clone, and the second argument is the prompts that will be added and merged with the original props passed into the component.     

react.children - which provides utilities for dealing with the props.children data structure. The most important method is the map 
                 function. React.children.map is very similar to the map function from arrays and invokes a function in every child contained within its children prop, performing a transformation and returning a new element.             

4) - Spread Attributes
The spread operator can be applied to different data types in JavaScript such as arrays, objects and even strings. The spread operator is a great tool that enables the creation of more flexible components, especially when forwarding props automatically to other components that expect them as well as providing your consumers with a nice component. API.




* Reusing behavior *

5) - Cross-cutting concerns in React
cross-cutting concerns include authentication, logging, error handling, and data fetching. Handling cross-cutting concerns in React can be a bit challenging because these concerns often span multiple components, making it difficult to manage the code in a modular and maintainable way.

6) - Higher-order components
Higher-order components (HOCs) are a powerful feature of the React library. They allow you to reuse component logic across multiple components. In React, a higher-order component is a function that takes a component as an argument and returns a new component that wraps the original component.

7) - Render props
Render props in react allow components to reference a function that returns a React element instead of implementing their own rendering logic. We can pass functions as render props in react. Instead of implementing its own render logic, a child component calls render props as functions.




* Integration tests with React Testing Library *

8) - Jest and the React Testing Library
Jest - Jest is a JavaScript test runner that lets you access an artificial DOM called JSDOM. While JSDOM is only an approximation of how 
       the browser works, it is often good enough for testing React components. Jest provides a good iteration speed combined with powerful features like mocking modules.
React Testing Library - which is a set of utilities that let you test React components without relying on their implementation details. It
                        has been designed to fulfill all the best practices highlighted before, so that you get a well-configured testing environment out of the box, and are able to focus on the business logic your tests need to run assertions on.       