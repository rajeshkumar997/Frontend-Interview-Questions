# Frontend-Interview-Questions

## 1- What are semantic and non-semantic elements in HTML?
## Semantic Elements- 
- [ ] they have meaning
- [ ] they describe how the content within them is supposed to behave
- [ ] Describe the purpose and structure of the content
- [ ] Important for accessibility and SEO
- [ ] Example- header, nav, article, section, aside, and footer
## Non-Semantic Element- 
- [ ] they don’t have meaning
- [ ] Used for styling and formatting purposes
- [ ] Examples - div, span, font, and b

## 2- What is the difference between position relative and position absolute? <br/>
https://codingbff.medium.com/difference-between-css-position-absolute-versus-relative-35f064384c6#:~:text=In%20a%20nutshell%20%E2%80%A6,changing%20the%20layout%20around%20it.

## 3- What is a flex box?
A flex box, or flexible box layout, is a layout mode in CSS that allows you to create flexible and responsive layouts for webpages. With flexbox, you can easily align, distribute, and rearrange elements within a container.
<br/>
https://www.freecodecamp.org/news/css-flexbox-complete-guide/

## 4- What is a box model in css?
The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.
<br/>
https://www.w3schools.com/css/css_boxmodel.asp

## 5- What is an event loop in javascript?
JavaScript has a runtime model based on an event loop, which is responsible for executing the code, collecting and processing events, and executing queued sub-tasks. This model is quite different from models in other languages like C and Java.
<br/>
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Event_loop

## 6- What is DOM?
The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.
<br/>
https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction

## 7- What is hoisting in javascript?
In JavaScript, hoisting allows you to use functions and variables before they're declared.
<br/>
https://www.freecodecamp.org/news/what-is-hoisting-in-javascript/

## 8- What is closure in javascript?
A closure is the combination of a function bundled together (enclosed) with references to its surrounding state (the lexical environment). In other words, a closure gives you access to an outer function's scope from an inner function.
<br/>
https://www.freecodecamp.org/news/lets-learn-javascript-closures-66feb44f6a44/

## 9- What is callback hell ?
Callback hell is a phenomenon that happens when multiple callbacks are nested on top of each other.
<br/>
https://www.scaler.com/topics/callback-hell-in-javascript/

## 10- What is the promise and how many parameters do they have?
A promise is an object that may produce a single value some time in the future: either a resolved value, or a reason that it’s not resolved (e.g., a network error occurred). A promise may be in one of 3 possible states: fulfilled, rejected, or pending. Promise users can attach callbacks to handle the fulfilled value or the reason for rejection.
<br/>
https://www.learnhowtoprogram.com/intermediate-javascript/asynchrony-and-apis/introduction-to-promises#:~:text=A%20promise%20generally%20takes%20a,async%20code%20goes%20here%20%7D)%3B

## 11- What is map, filter and reduce in javascript?
Map, reduce, and filter are all array methods in JavaScript. Each one will iterate over an array and perform a transformation or computation. Each will return a new array based on the result of the function.
<br/>
https://www.freecodecamp.org/news/map-filter-reduce-in-javascript/

## 12- How many scopes in javascript?
Scope determines the accessibility (visibility) of variables.

JavaScript has 3 types of scope:-
- [ ] Block scope
- [ ] Function scope
- [ ] Global scope <br/>
https://www.w3schools.com/js/js_scope.asp#:~:text=JavaScript%20has%203%20types%20of,Global%20scope

## 13- What is call, bind, apply in javascript? <br/>
Call is a function that helps you change the context of the invoking function. In layperson's terms, it helps you replace the value of this inside a function with whatever value you want.

Apply is very similar to the call function. The only difference is that in apply you can pass an array as an argument list.

Bind is a function that helps you create another function that you can execute later with the new context of this that is provided.
https://www.freecodecamp.org/news/understand-call-apply-and-bind-in-javascript-with-examples/

## 14- What is ‘this’ keyword in javascript?
“This” keyword refers to an object that is executing the current piece of code. It references the object that is executing the current function. If the function being referenced is a regular function, “this” references the global object. <br />
https://www.freecodecamp.org/news/the-this-keyword-in-javascript/

## 15- What is the difference between normal function and arrow function?
Regular functions created using function declarations or expressions are constructible and callable. Since regular functions are constructible, they can be called using the new keyword. However, the arrow functions are only callable and not constructible, i.e arrow functions can never be used as constructor functions. <br />
https://www.freecodecamp.org/news/the-difference-between-arrow-functions-and-normal-functions/

## 16- What is memoization in javascript?
Memoization in javascript is an optimization technique that stores the results of function calls in a temporary data structure and then retrieves the results whenever the stored result is needed in the program. By doing this, the execution time is reduced and the CPU performance is increased. <br />
https://www.freecodecamp.org/news/memoization-in-javascript-and-react/

## 17- What is the rest and spread operator in javascript?
The rest operator (…) allows us to call a function with any number of arguments and then access those excess arguments as an array. The rest operator also allows us in destructuring array or objects.
The spread operator (…) allows us to expand an iterable like array into its individual elements. <br />
https://www.freecodecamp.org/news/javascript-rest-vs-spread-operators/

## 18- What is virtual DOM?
DOM stands for Document Object Model it is the structural representation of all nodes in an HTML document DOM represents the Ul of your applications.  DOM manipulation is required to dynamically change the content of a web page. DOM is an interface that allows the script to update the content, style, and structure of the document. <br />
https://www.geeksforgeeks.org/difference-between-virtual-dom-and-real-dom/

## 19- What are the advantages and disadvantages of React.js?
https://massivepixel.io/blog/react-advantages-disadvantages/

## 20- What is one way data binding?
React is an open-source JavaScript library for building user interfaces or UI components. It is widely used to design simple views for each state in the application, and efficiently update and render just the right components when the data changes. React supports one-way data binding which means a unidirectional data-flow. <br/>
https://medium.com/@tangrianand/understanding-one-way-data-binding-in-react-77fdb13db312

## 21- What is redux and how does it work?
https://redux.js.org/tutorials/fundamentals/part-1-overview    <br/>
https://www.freecodecamp.org/news/what-is-redux-store-actions-reducers-explained/

## 22- What is a higher order component?
A higher-order component is a function that takes in a component and returns a new component. <br />
https://blog.logrocket.com/understanding-react-higher-order-components/#:~:text=A%20higher%2Dorder%20component%20is,will%20be%20the%20enhanced%20component

## 23- What is the lifecycle method in react.js?
Each component in React has a lifecycle which you can monitor and manipulate during its three main phases. The three phases are: Mounting, Updating, and Unmounting. <br />
https://blog.logrocket.com/react-lifecycle-methods-tutorial-examples/

## 24- What is the difference between the local storage and session storage?
The difference between sessionStorage and localStorage is that localStorage data does not expire, whereas sessionStorage data is cleared when the browser tab is closed. <br />
https://www.geeksforgeeks.org/difference-between-local-storage-session-storage-and-cookies/

## 25- Why is React so popular?
React, compared to other popular frontend frameworks like Angular & Vue, is much easier to learn. In fact, it's one of the main reasons why React gained so much traction in little time. It helps businesses quickly build their projects. <br />
https://www.peerbits.com/blog/reasons-to-choose-reactjs-for-your-web-development-project.html#:~:text=It's%20easy%20to%20learn,businesses%20quickly%20build%20their%20projects.

## 26- What are react fragments?
React Fragments allow you to wrap or group multiple elements without adding an extra node to the DOM. This can be useful when rendering multiple child elements/components in a single parent component. <br/>
https://legacy.reactjs.org/docs/fragments.html

## 27- What is the difference between state and props?
https://www.geeksforgeeks.org/what-are-the-differences-between-props-and-state/

## 28- What are hooks in react and what is the difference between useMemo and useContext hook?

