---------------
Interactive CSS
---------------




* Creating Layouts *

1) - CSS web layout
layout is one of the most important components of designing a good web page because layouts help divide a page into different sections, thus making the page more presentable. 

2) - flexbox
The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning. you want to lay a collection of items out in one direction or another. As you lay out your items you want to control the dimensions of the items in that one dimension, or control the spacing between items.

3) - Flex charts
The FlexChart allows you to select series or data points by clicking or touching them. Use the selectionMode property to specify whether you want to allow selection by series, by data point, or no selection at all. The most important property when using flex is the flex property that in turn has the following three sub properties. Flex grow, which specifies how much the item will grow compared to other flexible items, flex shrink, which specifies how much the item will shrink compared to other flexible items. And flex basis, which specifies the initial length of the flexible item. 

4) - CSS grids
CSS Grids are two-dimensional design layouts that are responsive and compatible with browser variations. They are an alternative to other options such as Flexboxes and tables, especially when you are working with larger scale layouts.




* CSS Selectors *

5) - Selectors
CSS selectors correspond to specific elements or element groups in an HTML document.element or type selectors. 
element selector - It allows developers to select html elements based on their element type.
ID selectors - This Selectors use the ID attribute of html element. 
Class selectors - It allow you to select elements based on the class attribute applied to them. With class selectors, you can apply rules to all elements with the specified class name. 
Attribute selectors - It match the attribute of value for a given element. 
star selectors - It is used for selecting all the elements of a web page. It will affect all the elements in the html file. 
If you want to apply the same styling to more than one type of element, like the heading one and paragraph elements you can use group selectors.

6) - Combination selectors
CSS makes it possible to combine more than one selector so that you can apply rules to elements based on their relationship with one another. You do this with combination selectors, and there are four main types. Namely, descendant selectors, child selectors, general sibling selectors and adjacent sibling selectors.
Descendant selectors - This are useful if you need to select HTML elements that are contained within another selector. 
Child selectors - It update the previous selector to a child selector by adding a close angle bracket in between the two selectors.
general sibling selectors - which apply rules to all the selectors of the same type that follow the first type. 

7) - Pseudo-classes
pseudo-classes are state-based selectors, which means that they allow you to select elements based on their state. You use pseudo-class selectors to improve the interactivity of web pages by styling elements in response to user input.




* CSS Effects *

8) - What is an effect
It is a change that is a result or consequence of an action or other cause animations are a type of effect that has brought life like quality to web pages. Effects help highlight the special features on a given page. CSS styling and effects improve the creativity and aesthetics of websites. But too much of it can also lead to distraction and drive users away from the page. 

9) - CSS Transforms and transitions
The Syntax of the transform and transition properties are similar. You simply add transform or transition and the value. 
The transform property - It modifies the spatial position of an element. For instance, it can change its scale and angle.
The transitions property - It allows you to change property values smoothly, over a given duration.

10) - CSS animation
When developers want to create complex animations, they use the animation property. But to control the execution of the steps of the animation, they use the @keyframe rule. The @keyframe rule can also use the optional keywords, from and to, to show transitions.

11) - Preprocessors: sass, scss
CSS preprocesses are special compilers used to create a CSS file that can be referenced by an HTML document. They are generally used to reduce the amount of CSS you need to write and allow you to re-use values across multiple rules.
SASS - Syntactically Awesome Style Sheets (SASS) is a scripting language that CSS compiles and interprets into CSS. 
       SASS code is processed by the program and compiled into CSS code, which can be used to style HTML elements.
SCSS - which stands for Sassy CSS. extend the default capabilities of CSS. They enable us to use logic in our CSS code, such as variables, 
       nesting, inheritance, mixins, functions, and mathematical operations.




* Debugging *

12) - Common errors
The common errors that developers make can broadly be classified as skill-based, rule-based, and knowledge-based. Many skill-based errors can be classified as typos. That is to say, they are mistakes made when typing in the code. 

13) - Debugging the front-end
Debugging front-end code is using the browser dev tools extensively. They provide a powerful set of features for inspecting, modifying, and debugging HTML, CSS, and JavaScript elements in real-time.

14) - Debugging tools
There are different diagnostic functions that the developer tools provide. These include viewing error logs, debugging JavaScript code, inspecting HTTP requests and responses, inspecting performance and memory usage of JavaScript code, inspecting CSS grid and flexbox layouts, inspecting HTML and CSS rendering, and live editing.

15) - UI testing
UI testing strategies to ensure optimal customer satisfaction. UI testing is a complex area with many techniques and strategies used by developers. The strategies you will use will often be determined by business priority, customer requirements, and project timelines. 
The most common strategies used during development are; automated user acceptance testing, cross-device testing, and visual regression testing. Cross-device testing - It involves the manual or automated use of different devices to test the layout and behavior of an application. The goal of this testing strategy is to ensure user experience consistency between different devices. 