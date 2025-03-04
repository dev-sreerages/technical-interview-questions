# Index
## Frontend
- <a href="#javascript-technical-interview-questions-and-answers">Javascript</a>
- <a href="#react-technical-interview-questions-and-answers">React</a>
## Backend

# JavaScript Technical Interview Questions and Answers

## 1. What is JavaScript?
**Answer**: JavaScript is a high-level, interpreted programming language that conforms to the ECMAScript specification. It is widely used for web development to create interactive and dynamic web pages.

## 2. What are the data types in JavaScript?
**Answer**: JavaScript has the following data types:
- Primitive: Number, String, Boolean, Null, Undefined, Symbol, and BigInt.
- Non-Primitive: Object (including Arrays, Functions, and more).

## 3. What is the difference between `let`, `var`, and `const`?
**Answer**:
- `var`: Function-scoped, can be re-declared and updated.
- `let`: Block-scoped, cannot be re-declared but can be updated.
- `const`: Block-scoped, cannot be re-declared or updated (values can be mutable if they are objects or arrays).

## 4. What is hoisting in JavaScript?
**Answer**: Hoisting is JavaScript's default behavior of moving declarations to the top of the current scope (function or global). This means variables and functions can be used before they are declared.

## 5. What is the difference between `==` and `===`?
**Answer**:
- `==` (loose equality): Compares values for equality, performing type conversion if necessary.
- `===` (strict equality): Compares values for equality without type conversion.

## 6. What is a closure?
**Answer**: A closure is a function that retains access to its lexical scope, even when the function is executed outside that scope. It allows for data privacy and maintaining state.

## 7. What is the event loop?
**Answer**: The event loop is a mechanism that allows JavaScript to perform non-blocking I/O operations, despite being single-threaded. It continuously checks the message queue and executes callbacks as needed.

## 8. What are Promises?
**Answer**: Promises are objects that represent the eventual completion (or failure) of an asynchronous operation. They have three states: pending, fulfilled, and rejected.

## 9. What is async/await?
**Answer**: `async/await` is a syntactic sugar built on Promises, allowing you to write asynchronous code in a synchronous manner. It makes the code easier to read and maintain.

## 10. What is the difference between `call`, `apply`, and `bind`?
**Answer**:
- `call`: Invokes a function with a specified `this` context and arguments provided individually.
- `apply`: Invokes a function with a specified `this` context and arguments provided as an array.
- `bind`: Creates a new function with a specified `this` context and optionally, initial arguments.

## 11. What is the difference between `undefined` and `null`?
**Answer**:
- `undefined`: A variable that has been declared but has not been assigned a value.
- `null`: An assignment value that represents no value or no object.

## 12. What is the `this` keyword?
**Answer**: The `this` keyword refers to the context in which a function is executed. Its value depends on how the function is called (e.g., as a method, constructor, or standalone function).

## 13. What are arrow functions?
**Answer**: Arrow functions are a shorter syntax for function expressions that do not have their own `this`, `arguments`, `super`, or `new.target` bindings. They are often used for concise function expressions.

## 14. What is the spread operator?
**Answer**: The spread operator (`...`) allows an iterable (e.g., array or object) to be expanded in places where zero or more arguments or elements are expected. It can be used for copying or merging arrays and objects.

## 15. What is destructuring?
**Answer**: Destructuring is a syntax that allows you to unpack values from arrays or properties from objects into distinct variables.

## 16. What are template literals?
**Answer**: Template literals are string literals that allow embedded expressions. They are enclosed by backticks (`` ` ``) and can contain placeholders indicated by `${expression}`.

## 17. What is the DOM?
**Answer**: The Document Object Model (DOM) is an interface that represents the structure of a document (e.g., HTML or XML) and allows scripts to interact with and manipulate the document's content and structure.

## 18. What is the difference between `innerHTML` and `textContent`?
**Answer**:
- `innerHTML`: Gets or sets the HTML content of an element, including tags.
- `textContent`: Gets or sets the text content of an element, excluding tags.

## 19. What are event delegation and event bubbling?
**Answer**:
- **Event Delegation**: A technique of handling events by using a single event listener on a parent element to manage events for multiple child elements.
- **Event Bubbling**: A process where an event starts from the target element and propagates upward through the DOM hierarchy.

## 20. What is a prototype in JavaScript?
**Answer**: A prototype is an object from which other objects inherit properties and methods. Every JavaScript object has a prototype, which is used for inheritance and property sharing.

## 21. What is the difference between `map`, `filter`, and `reduce`?
**Answer**:
- `map`: Creates a new array by applying a function to each element of an existing array.
- `filter`: Creates a new array with elements that pass a specified test.
- `reduce`: Reduces an array to a single value by applying a function to each element and accumulating the result.

## 22. What is the purpose of the `fetch` API?
**Answer**: The `fetch` API provides a modern way to make network requests and handle responses. It returns a Promise that resolves to the Response object.

## 23. What is the difference between function declarations and function expressions?
**Answer**:
- **Function Declarations**: Function statements that are hoisted to the top of their scope.
- **Function Expressions**: Functions defined within an expression and not hoisted.

## 24. What is a callback function?
**Answer**: A callback function is a function passed as an argument to another function, allowing it to be called back at a later time.

## 25. What is the purpose of `Array.prototype.slice`?
**Answer**: `Array.prototype.slice` creates a shallow copy of a portion of an array into a new array object, without modifying the original array.

## 26. What is the difference between synchronous and asynchronous code?
**Answer**:
- **Synchronous Code**: Code that is executed sequentially, blocking the execution of subsequent code until the current operation completes.
- **Asynchronous Code**: Code that allows other operations to be performed while awaiting the completion of an asynchronous task.

## 27. What is the `typeof` operator?
**Answer**: The `typeof` operator returns a string indicating the type of the operand. It can be used to check the data type of a variable.

## 28. What is the purpose of `Array.prototype.forEach`?
**Answer**: `Array.prototype.forEach` executes a provided function once for each array element. It is used for iterating over arrays.

## 29. What is the difference between `Object.keys` and `Object.values`?
**Answer**:
- `Object.keys`: Returns an array of a given object's own enumerable property names.
- `Object.values`: Returns an array of a given object's own enumerable property values.

## 30. What is the `bind` method in JavaScript?
**Answer**: The `bind` method creates a new function that, when called, has its `this` keyword set to the provided value, with a given sequence of arguments.

## 31. What is the difference between `window.onload` and `document.ready`?
**Answer**:
- `window.onload`: Fires when the entire page (including all dependent resources) has loaded.
- `document.ready`: Fires when the DOM is fully loaded and parsed, without waiting for stylesheets, images, and subframes to finish loading.

## 32. What is an IIFE (Immediately Invoked Function Expression)?
**Answer**: An IIFE is a function that is executed immediately after it is defined. It is used to create a new scope and avoid polluting the global scope.

## 33. What is the `new` keyword in JavaScript?
**Answer**: The `new` keyword is used to create an instance of a user-defined object type or a built-in object with a constructor function.

## 34. What is the purpose of `Array.prototype.concat`?
**Answer**: `Array.prototype.concat` is used to merge two or more arrays, returning a new array without modifying the original arrays.

## 35. What is the event object in JavaScript?
**Answer**: The event object represents an event that takes place in the DOM. It contains properties and methods related to the event, such as `target`, `type`, and `preventDefault`.

## 36. What is debouncing?
**Answer**: Debouncing is a technique used to limit the rate at which a function is executed. It ensures that a function is invoked only once after a specified period of inactivity.

## 37. What is throttling?
**Answer**: Throttling is a technique used to limit the rate at which a function is executed. It ensures that a function is invoked at most once in a specified period.

## 38. What is the difference between shallow and deep copying?
**Answer**:
- **Shallow Copying**: Creates a copy of an object's structure, but not the nested objects.
- **Deep Copying**: Creates a copy of an object and all its nested objects, resulting in a completely independent copy.

## 39. What is the `instanceof` operator?
**Answer**: The `instanceof` operator checks if an object is an instance of a specific constructor or class. It returns `true` if the object is an instance, otherwise `false`.

## 40. What are template literals?
**Answer**: Template literals are string literals that allow embedded expressions. They are enclosed by backticks (`` ` ``) and can contain placeholders indicated by `${expression}`.

## 41. How do you handle exceptions in JavaScript?
**Answer**: Exceptions in JavaScript are handled using `try...catch` blocks, where code that may throw an exception is placed in the `try` block, and the error handling code is placed in the `catch` block.

## 42. What is the purpose of `Object.assign`?
**Answer**: `Object.assign` is used to copy the values of all enumerable own properties from one or more source objects to a target object. It returns the target object.

## 43. What is the difference between `==` and `===`?
**Answer**:
- `==` (loose equality): Compares values for equality, performing type conversion if necessary.
- `===` (strict equality): Compares values for equality without type conversion.

## 44. What is the `nullish coalescing operator`?
**Answer**: The nullish coalescing operator (`??`) is a logical operator that returns its right-hand operand when its left-hand operand is `null` or `undefined`, otherwise it returns its left-hand operand.

## 45. What are JavaScript modules?
**Answer**: JavaScript modules allow you to break up your code into separate files and import/export functionalities between them. They help in organizing and maintaining a codebase.

## 46. What is a promise chain?
**Answer**: A promise chain is a series of `.then` calls on a promise, where each `.then` returns a new promise. It allows for sequential asynchronous operations.

## 47. What is the `Symbol` data type?
**Answer**: `Symbol` is a primitive data type introduced in ES6. It is used to create unique identifiers for object properties, ensuring they do not clash with other property keys.

## 48. What is the purpose of `Array.prototype.find`?
**Answer**: `Array.prototype.find` returns the first element in an array that satisfies the provided testing function. If no elements satisfy the testing function, it returns `undefined`.

## 49. What is event propagation?
**Answer**: Event propagation is the process by which an event travels through the DOM tree. It includes three phases: capturing phase, target phase, and bubbling phase.

## 50. What is the purpose of the `finally` block in a `try...catch` statement?
**Answer**: The `finally` block contains code that will always execute after the `try` and `catch` blocks, regardless of whether an exception was thrown or caught. It is used for cleanup operations.

---

# React Technical Interview Questions and Answers

## 1. What is React?
**Answer**: React is a JavaScript library for building user interfaces, mainly for single-page applications. It's used for handling the view layer for web and mobile apps.

## 2. What are the main features of React?
**Answer**: The main features of React are:
- JSX: JavaScript XML syntax used to create elements.
- Components: Reusable pieces of UI.
- Virtual DOM: Efficiently updates and renders components.
- Unidirectional Data Flow: Data flows in one direction, making it easier to debug.

## 3. What is JSX?
**Answer**: JSX stands for JavaScript XML. It's a syntax extension for JavaScript that looks similar to XML and is used with React to describe what the UI should look like.

## 4. What is the Virtual DOM?
**Answer**: The Virtual DOM is a lightweight copy of the actual DOM. React uses it to optimize updates by comparing it with the real DOM and updating only the changed parts.

## 5. What are React Components?
**Answer**: Components are the building blocks of a React application. They are reusable pieces of UI that can be functional or class-based.

## 6. What is the difference between state and props?
**Answer**: 
- **State**: Local data storage that is managed within the component.
- **Props**: Read-only data passed from parent to child components.

## 7. What are hooks in React?
**Answer**: Hooks are functions that let you use state and other React features in functional components. Examples include useState, useEffect, and useContext.

## 8. What is the useState hook?
**Answer**: useState is a hook that lets you add state to functional components. It returns an array with the current state value and a function to update it.

## 9. What is the useEffect hook?
**Answer**: useEffect is a hook that lets you perform side effects in functional components, such as data fetching, subscriptions, and manual DOM manipulations.

## 10. What is the context API?
**Answer**: The context API is a way to pass data through the component tree without having to pass props down manually at every level.

## 11. How do you create a React component?
**Answer**: You can create a React component using a function or a class. Functional components use a function to return JSX, while class components extend React.Component and use a render method.

## 12. What is a higher-order component (HOC)?
**Answer**: A higher-order component is a function that takes a component and returns a new component with added functionality.

## 13. How do you handle events in React?
**Answer**: Events in React are handled using camelCase syntax for event names and passing event handler functions directly in JSX.

## 14. What is the purpose of keys in React?
**Answer**: Keys help React identify which items have changed, been added, or removed. They should be unique and stable.

## 15. What is the difference between controlled and uncontrolled components?
**Answer**: 
- **Controlled Components**: Form inputs that derive their value from the component state.
- **Uncontrolled Components**: Form inputs that maintain their own state.

## 16. How do you lift state up in React?
**Answer**: Lifting state up involves moving the state to a common ancestor component so that it can be shared between multiple child components.

## 17. What is Redux?
**Answer**: Redux is a state management library for JavaScript applications. It provides a predictable state container and follows principles such as a single source of truth and immutable state updates.

## 18. How do you use Redux with React?
**Answer**: To use Redux with React, you need to create a store, define reducers, and use the Provider component to pass the store to your React components. You can then use hooks like useSelector and useDispatch to interact with the store.

## 19. What is the purpose of middleware in Redux?
**Answer**: Middleware in Redux provides a way to extend Redux with custom functionality, such as logging, handling asynchronous actions, and error reporting.

## 20. What is React Router?
**Answer**: React Router is a library for routing in React applications. It enables navigation between different components and allows for dynamic routing.

## 21. How do you handle forms in React?
**Answer**: Forms in React can be handled using controlled components, where the form inputs are tied to the component state, or using libraries like Formik for more complex forms.

## 22. What is the difference between useEffect and useLayoutEffect?
**Answer**: 
- **useEffect**: Runs after the render is committed to the screen.
- **useLayoutEffect**: Runs synchronously after all DOM mutations but before the browser has a chance to paint.

## 23. What are React Fragments?
**Answer**: React Fragments let you group multiple elements without adding extra nodes to the DOM. They are used to return multiple elements from a component.

## 24. How do you optimize performance in a React application?
**Answer**: Performance optimization techniques include using React.memo, useCallback, useMemo, code-splitting, lazy loading, and avoiding unnecessary re-renders.

## 25. What is the useReducer hook?
**Answer**: useReducer is a hook that provides an alternative to useState for more complex state logic. It takes a reducer function and an initial state and returns the current state and a dispatch function.

## 26. How do you handle errors in React?
**Answer**: Errors in React can be handled using error boundaries, which catch JavaScript errors anywhere in their child component tree and render a fallback UI.

## 27. What is PropTypes in React?
**Answer**: PropTypes is a library for type-checking the props passed to a component, ensuring they are of the correct type and shape.

## 28. What is the difference between class components and functional components?
**Answer**: 
- **Class Components**: Use ES6 classes, have lifecycle methods, and manage state with this.state.
- **Functional Components**: Use functions, can use hooks for state and lifecycle methods, and are generally simpler and easier to test.

## 29. What is the useRef hook?
**Answer**: useRef is a hook that returns a mutable ref object whose .current property is initialized to the passed argument. It can be used to access DOM elements directly.

## 30. How do you perform data fetching in React?
**Answer**: Data fetching in React can be done using the useEffect hook along with fetch API, Axios, or other data-fetching libraries.

## 31. What is code-splitting?
**Answer**: Code-splitting is a technique to split your code into smaller bundles, which can be loaded on demand. This improves the performance of your application by reducing the initial load time.

## 32. What is lazy loading in React?
**Answer**: Lazy loading in React is the process of loading components only when they are needed. This can be achieved using React.lazy and Suspense.

## 33. What is the purpose of React.StrictMode?
**Answer**: React.StrictMode is a tool for highlighting potential problems in an application. It activates additional checks and warnings for its descendants.

## 34. What is the useCallback hook?
**Answer**: useCallback is a hook that returns a memoized callback function, which helps to prevent unnecessary re-renders by ensuring the same instance of the function is used unless its dependencies change.

## 35. What is the useMemo hook?
**Answer**: useMemo is a hook that returns a memoized value. It helps to optimize performance by memoizing the result of an expensive computation and recomputing it only when its dependencies change.

## 36. How do you handle side effects in React?
**Answer**: Side effects in React can be handled using the useEffect hook. This hook allows you to perform actions like data fetching, subscriptions, and manually changing the DOM.

## 37. What is React Context?
**Answer**: React Context provides a way to pass data through the component tree without having to pass props down manually at every level. It is useful for global state management.

## 38. What is server-side rendering (SSR)?
**Answer**: Server-side rendering is the process of rendering React components on the server and sending the generated HTML to the client. This improves performance and SEO.

## 39. What is the use of React.PureComponent?
**Answer**: React.PureComponent is a base class for components that only re-render when their props or state change. It provides a shallow comparison of props and state to optimize performance.

## 40. What is the difference between useState and useReducer?
**Answer**: 
- **useState**: Simplest way to manage state in a functional component.
- **useReducer**: More powerful and flexible way to manage state, especially for complex state logic.

## 41. What is React's reconciliation algorithm?
**Answer**: React's reconciliation algorithm, also known as the Diffing algorithm, is used to determine the minimal number of changes needed to update the UI efficiently.

## 42. What is the purpose of React.memo?
**Answer**: React.memo is a higher-order component that memoizes the rendered output of a functional component, preventing unnecessary re-renders when the props haven't changed.

## 43. What is the difference between React and React Native?
**Answer**: 
- **React**: Library for building web applications.
- **React Native**: Framework for building mobile applications using React.

## 44. How do you handle authentication in a React application?
**Answer**: Authentication can be handled using libraries like Firebase, Auth0, or by implementing custom authentication logic with JWT tokens and context for state management.

## 45. What are portals in React?
**Answer**: Portals provide a way to render children into a DOM node that exists outside the DOM hierarchy of the parent component.

## 46. How do you test React components?
**Answer**: React components can be tested using frameworks and libraries like Jest, React Testing Library, and Enzyme to perform unit, integration, and end-to-end testing.

## 47. What is the purpose of the useImperativeHandle hook?
**Answer**: useImperativeHandle is a hook that customizes the instance value that is exposed to parent components when using ref. It is used in conjunction with forwardRef.

## 48. How do you manage global state in a React application?
**Answer**: Global state can be managed using Context API, Redux, or other state management libraries like MobX or Zustand.

## 49. What is the difference between synchronous and asynchronous state updates in React?
**Answer**: 
- **Synchronous State Updates**: Occur immediately and are handled by the React event loop.
- **Asynchronous State Updates**: May be batched and processed later to optimize performance.

## 50. How do you handle routing in a React application?
**Answer**: Routing in a React application can be handled using React Router, which provides components and hooks for navigating between different views and managing URL parameters.

---

