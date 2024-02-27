--------------
Data and State
--------------




* Dynamic events and how to handle them *

1) - Types of events
Developers can use events to execute JavaScript's code in response to an action based on user interactivity, like clicking a button. HTML button communicates to the JavaScript event handler to execute some code and respond to the event action is known as triggering.

There are many events supported in React, which can be divided into several groups. Those groups include clipboard events, composition Events, keyboard events, and many more. Each group usually holds multiple events. mouse events include onClick, onContextMenu, onDoubleClick, and several others. You will also find that the clipboard group has the useful events: onCopy, onCuts, and onPaste.

2) - Event handling
Event handling in React enables a user to interact with a webpage and take specified action whenever an event, like a click or a hover, takes place. Event handling in React is overall quite similar to HTML. But note that there is no function invocation syntax in event handling attribute in React. In React, you should not invoke a function. Instead, you just pass a reference to the event handling function without invoking it.




* Data and Events *

3) - Parent-child data flow
In React, the primary method of passing data from a parent component to a child component is through props. Props are read-only and allow the parent component to pass data down the component tree. By storing data in the parent component, you can dynamically pass it to the child component without the need to update children individually.

4) - Hooks
Hooks allow function components to have access to state and other React features. It creates a state variable with an initial value that represents the current state. And it creates a function to set that states variable value. One key benefit of hooks is that they solve the problem of unnecessary code reuse across components.

useState hook - it is the most commonly used one. This hook is used to manage the state within a component and keep track of it and it's
                 built directly into React.

5) - State
All the data in React can be divided into props data and states data. State as a component's internal data that determines the current behavior of a component. It's often used to store data that affects the behavior of a component. The state data belongs to the component itself like data inside the components that it controls and can mutate.                 

6) - Prop drilling
prop drilling is a situation where you are passing data from a parent to a child component, then to a grandchild component, and so on, until it reaches a more distant component further down the component tree, where this data is required.

7) - React state management
React components have a built-in state object. The state is encapsulated data where you store assets that are persistent between component renderings.

8) - Stateful vs. stateless
stateless components - Stateless components are easy to use and can be reused in different parts of your app. Use stateless components when 
                       your component doesn't need to maintain its own state in order to work.
Stateful components - Stateful components are more complex and are used to manage state and handle user events. Use stateful components 
                      when your component does need to maintain its own state in order to work.