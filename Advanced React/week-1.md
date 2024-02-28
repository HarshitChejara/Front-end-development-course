----------
Components
----------




* Randering Lists in React *

1) - Transforming lists in JavaScript
The map method is use in JavaScript to transform lists of data. It creates an array from calling a specific function on each item in the parent array. .map() is a non-mutating method that creates a new array, as opposed to mutating methods, which only make changes to the calling array.

2) - Render a simple list component
The map() function is a powerful tool for rendering lists in React. It takes an array, applies a function to each item, and returns a new array with the results. In the context of React, the map() function is used to create an array of JSX elements that represent the items in the list.

3) - Keys in React
It is a special string attribute you need to include when creating lists of elements in React. Keys are identifier's that help React to determine which items have changed or added or are removed. They also instruct how to treat a specific element when an update occurs and whether its internal state should be preserved or not. 




* Forms in React *

4) - controlled components
Controlled components are a set of components that offer a declarative application programming interface or API to enable full control of the state of form elements at any point in time using React state. It enables react to be the source of truth for the state of your form inputs.

In a controlled component, form data is handled by a React component. The alternative is uncontrolled components, where form data is handled by the DOM itself. To write an uncontrolled component, instead of writing an event handler for every state update, you can use a ref to get form values from the DOM.




* React Context *

5) - Props and State
props and state are both plain javascript or Js objects. The react uses to hold information.
they are different in one important way props get passed to the component like parameters in a function where state is managed within the component like variables declared within a function.

Props - props which is a shorthand for properties are a components configuration. They are received from parents in the tree and are immutable as far as the component receiving them is concerned. A component cannot change its props but it is responsible for putting together the props of its child components. 

State - This object is a way to allow react to determine when it should re render a component. states Life cycle starts with a default value when a component mount and then modifications of that value happen over time. It is a serialize double representation of one point in time.

6) - Context, and it's use
Context provides an alternative way to pass data through the component tree without having to pass props down manually at every level. It is the right tool when you need to share data that can be considered global for a tree of React components. One such tool is the useContext hook, which allows developers to easily share data across multiple components without the need for prop drilling.