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
</br>
https://www.tutorialstonight.com/js/js-dom-introduction

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
```js
// a promise
let promise = new Promise((resolve, reject) => {
  setTimeout(() => {
    resolve('promise resolved');
  }, 4000);
});
// async function
async function asyncFunc() {
  try {
    // wait util the promise resolved
    let result = await promise();
    console.log(result);
  } catch (error) {
    console.log(error);
  }
}
// calling the async function
asyncFunc(); //promise resolved
```
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
## Props 
- [ ] The Data is passed from one component to another.
- [ ] It is Immutable (cannot be modified).
- [ ] Props can be used with state and functional components.
- [ ] Props are read-only.
## STATE 
- [ ] The Data is passed within the component only.
- [ ] It is Mutable ( can be modified).
- [ ] The state can be used only with the state components/class component
- [ ] The state is both read and write.
<br />
https://www.geeksforgeeks.org/what-are-the-differences-between-props-and-state/

## 28- What are hooks in react and what is the difference between useMemo and useContext hook?
Hooks allow function components to have access to state and other React features. Because of this, class components are generally no longer needed.

There are 3 rules for hooks:
- [ ] Hooks can only be called inside React function components.
- [ ] Hooks can only be called at the top level of a component.
- [ ] Hooks cannot be conditional
## Note: Hooks will not work in React class components.
The useMemo and useCallback Hooks are similar. The main difference is that useMemo returns a memoized value and useCallback returns a memoized function.
## useContext 
React Context is a way to manage state globally.
It can be used together with the useState Hook to share state between deeply nested components more easily than with useState alone.
<br />
https://www.w3schools.com/react/react_usememo.asp

## 29- What is the difference between map and forEach?
 The map() method is used to transform the elements of an array, whereas the forEach() method is used to loop through the elements of an array.
https://www.freecodecamp.org/news/4-main-differences-between-foreach-and-map/

## 30- How can you handle errors in react?
https://dev.to/jyotishman/how-to-handle-errors-effectively-in-react-js-dl2

## 31- What is render prop?
The term “render prop” refers to a technique for sharing code between React components using a prop whose value is a function.

A component with a render prop takes a function that returns a React element and calls it instead of implementing its own render logic.
```
<DataProvider render={data => (
  <h1>Hello {data.target}</h1>
)}/>
```
https://levelup.gitconnected.com/understanding-react-render-props-by-example-71f2162fd0f2#:~:text=The%20term%20%E2%80%9Crender%20prop%E2%80%9D%20refers,whose%20value%20is%20a%20function.&text=By%20using%20a%20prop%20to,being%20applied%20to%20the%20UI.

## 32- What are refs in react?
Refs is the shorthand used for references in React. It is similar to keys in React. It is an attribute which makes it possible to store a reference to particular DOM nodes or React elements. It provides a way to access React DOM nodes or React elements and how to interact with it. <br/>
https://blog.logrocket.com/complete-guide-react-refs/

## 33- What is the state of react?
The state is a built-in React object that is used to contain data or information about the component. A component's state can change over time; whenever it changes, the component re-renders. <br />
https://www.freecodecamp.org/news/what-is-state-in-react-explained-with-examples/

## 34- What are react portals?
React Portals are an advanced concept that allows developers to render their elements outside the React hierarchy tree without comprising the parent-child relationship between components. Usually, typical React components are located within the DOM. <br />
https://blog.logrocket.com/learn-react-portals-example/#:~:text=React%20Portals%20are%20an%20advanced,are%20located%20within%20the%20DOM.

## 35- What is prop drilling?
Prop drilling refers to the process of sending props from a higher-level component to a lower-level component. <br/>
https://www.freecodecamp.org/news/avoid-prop-drilling-with-react-context-api/ <br/>
https://www.geeksforgeeks.org/what-is-prop-drilling-and-how-to-avoid-it/ 

## 36- How to manage performance in react?

## 37- React Hooks-
## useState: 
- [ ] To manage states. Returns a stateful value and an updater function to update it.
## useEffect: 
- [ ] To manage side-effects like API calls, subscriptions, timers, mutations, and more.
## useContext: 
- [ ] To return the current value for a context.
## useReducer: 
- [ ] A useState alternative to help with complex state management.
## useCallback: 
- [ ] It returns a memorized version of a callback to help a child component not re-render unnecessarily.
## useMemo: 
- [ ] It returns a memoized value that helps in performance optimizations.
## useRef: 
- [ ] It returns a ref object with a .current property. The ref object is mutable. It is mainly used to access a child component imperatively.
## useLayoutEffect: 
- [ ] It fires at the end of all DOM mutations. It's best to use useEffect as much as possible over this one as the useLayoutEffect fires synchronously.
## useDebugValue: 
- [ ] Helps to display a label in React DevTools for custom hooks.

## 38- What is the difference between useMemo and useCallback?
  https://www.freecodecamp.org/news/better-react-performance-usecallback-vs-usememo/

## 39- What is the pure component in react?
  https://www.freecodecamp.org/news/higher-order-functions-in-javascript-explained/

## 40- What is a higher order function?
   https://www.freecodecamp.org/news/higher-order-functions-in-javascript-explained/
     </br>
   https://codepen.io/Mo-SlimedGhost/pen/abWeqXq
   
## 41- What is a prototype in javascript?
   https://www.geeksforgeeks.org/prototype-in-javascript/
  
## 42- What is the difference between HTML and HTML5?
   https://www.geeksforgeeks.org/difference-between-html-and-html5/
   </br>
   https://www.javatpoint.com/html-vs-html5

## 43- What is the difference between id and class?
   https://www.geeksforgeeks.org/difference-between-id-and-class-attributes-in-html/
   </br>
   https://www.javatpoint.com/css-class-vs-id
   
## 44- What is the difference between let, const and var?  
   https://www.freecodecamp.org/news/differences-between-var-let-const-javascript/#:~:text=If%20you%20never%20want%20a,is%20the%20keyword%20for%20you
   </br>
   https://www.geeksforgeeks.org/difference-between-var-let-and-const-keywords-in-javascript/
    </br>
   https://blog.webdevsimplified.com/2020-01/var-vs-let-vs-const/
   
## 45- What is the media query in css?
   https://www.w3schools.com/css/css3_mediaqueries.asp
   </br>
   https://www.geeksforgeeks.org/css-media-queries/
   
## 46- What is the difference between margin and padding?  
   https://www.geeksforgeeks.org/css-padding-vs-margin/
   </br>
   https://hackr.io/blog/margin-vs-padding
   </br>
   https://byjus.com/gate/difference-between-margin-and-padding/
   
   
## 47- What is a callback function in javascript?
   https://developer.mozilla.org/en-US/docs/Glossary/Callback_function
   </br>
   https://www.simplilearn.com/tutorials/javascript-tutorial/callback-function-in-javascript
   </br>
   https://www.freecodecamp.org/news/javascript-callback-functions-what-are-callbacks-in-js-and-how-to-use-them/
   
## 48- What is ajax?
   https://www.w3schools.com/whatis/whatis_ajax.asp
   </br>
   https://www.javatpoint.com/ajax-tutorial
   
## 49- What is the difference between null and undefined?
   https://wesbos.com/javascript/01-the-basics/types-null-and-undefined
   </br>
   https://www.javatpoint.com/null-vs-undefined
   
## 50- What are the new features in ES6?
   https://www.w3schools.com/js/js_es6.asp
   </br>
   https://www.boardinfinity.com/blog/top-10-features-of-es6/
   </br>
   https://www.freecodecamp.org/news/write-less-do-more-with-javascript-es6-5fd4a8e50ee2/

## 51- For vs forEach() vs for/in vs for/of in JavaScript?
  https://thecodebarbarian.com/for-vs-for-each-vs-for-in-vs-for-of-in-javascript.html

   
   
   
