# 300+ ReactJS Interview Q&A

> Click ⭐ if you like the project. Follow me [@sisi_tarak](https://www.linkedin.com/in/sisitarak) for more.

---

     Pull Request are highly recommended and appreciated.

---

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

| No. | Questions                                                                                                                                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [What is React?](#what-is-react)                                                                                                                                                                                                 |
| 2   | [What is the history behind React evolution?](#What-is-the-history-behind-react-evolution)                                                                                                                                       |
| 3   | [What are the major features of React?](#what-are-the-major-features-of-react)                                                                                                                                                   |
| 4   | [What is JSX in React?](#what-is-jsx-in-react)                                                                                                                                                                                   |
| 5   | [What are state and props in React?](#what-are-state-and-props-in-react)                                                                                                                                                         |
| 6   | [What is the significance of keys in React lists?](#what-is-the-significance-of-keys-in-react-lists)                                                                                                                             |
| 7   | [Explain the component lifecycle methods in React?](#explain-the-component-lifecycle-methods-in-react)                                                                                                                           |
| 8   | [What is the significance of setState in React?](#what-is-the-significance-of-setState-in-react)                                                                                                                                 |
| 9   | [Explain the concept of higher-order components in React?](#explain-the-concept-of-higher-order-components-in-react)                                                                                                             |
| 10  | [What are controlled components in React?](#what-are-controlled-components-in-react)                                                                                                                                             |
| 11  | [Explain the difference between functional components and class components in React?](#explain-the-difference-between-functional-components-and-class-components-in-react)                                                       |
| 12  | [What are React hooks?](#what-are-react-hooks)                                                                                                                                                                                   |
| 13  | [What are React Fragments?](#what-are-react-fragments)                                                                                                                                                                           |
| 14  | [What are refs in React?](#what-are-refs-in-react)                                                                                                                                                                               |
| 15  | [What is context in React?](#what-is-context-in-react)                                                                                                                                                                           |
| 16  | [Explain the concept of virtual DOM in React?](#explain-the-concept-of-virtual-dom-in-react)                                                                                                                                     |
| 17  | [What are keys and why are they important in React lists?](#what-are-keys-and-why-are-they-important-in-react-lists)                                                                                                             |
| 18  | [What are the differences between useState and useReducer hooks in React?](#what-are-the-differences-between-usestate-and-usereducer-hooks-in-react)                                                                             |
| 19  | [Explain the concept of lazy loading in React?](#explain-the-concept-of-lazy-loading-in-react)                                                                                                                                   |
| 20  | [What are the benefits of using PropTypes in React?](#what-are-the-benefits-of-using-proptypes-in-react)                                                                                                                         |
| 21  | [What are React hooks? Can you name a few built-in hooks and explain their use cases?](#what-are-react-hooks-can-you-name-a-few-built-in-hooks-and-explain-their-use-cases)                                                      |
| 22  | [Explain the concept of conditional rendering in React?](#explain-the-concept-of-conditional-rendering-in-react)                                                                                                                 |
| 23  | [What are the advantages of using arrow functions in React event handlers?](#what-are-the-advantages-of-using-arrow-functions-in-react-event-handlers)                                                                           |
| 24  | [What is the purpose of useEffect hook in React? How does it differ from componentDidMount and componentDidUpdate lifecycle methods?](#what-is-the-purpose-of-useeffect-hook-in-react-how-does-it-differ-from-componentdidmount-and-componentdidupdate-lifecycle-methods)                                                                                                                                                                                                                                 |
| 25  | [What are React portals?](#what-are-react-portals)                                                                                                                                                                               |
| 26  | [What is the purpose of React Router?](#what-is-the-purpose-of-react-router)                                                                                                                                                     |
| 27  | [Explain the concept of error boundaries in React?](#explain-the-concept-of-error-boundaries-in-react)                                                                                                                           |
| 28  | [What are controlled and uncontrolled components in React?](#what-are-controlled-and-uncontrolled-components-in-react)                                                                                                           |
| 29  | [What is the purpose of memo in React?](#what-is-the-purpose-of-memo-in-react)                                                                                                                                                   |
| 30  | [What is server-side rendering (SSR) in React? How does it differ from client-side rendering (CSR)?](#what-is-server-side-rendering-ssr-in-react-how-does-it-differ-from-client-side-rendering-csr)                              |
| 31  | [Explain the concept of code splitting in React?](#explain-the-concept-of-code-splitting-in-react)                                                                                                                               |
| 32  | [Explain the concept of React Suspense?](#explain-the-concept-of-react-suspense)                                                                                                                                                 |
| 33  | [What are the benefits of using React hooks over class components?](#what-are-the-benefits-of-using-react-hooks-over-class-components)                                                                                           |
| 34  | [Explain the concept of memoization in React?](#explain-the-concept-of-memoization-in-react)                                                                                                                                     |
| 35  | [What are the differences between React's setState() and useState() hooks?](#what-are-the-differences-between-reacts-setstate-and-usestate-hooks)                                                                                |
| 36  | [What is the purpose of the children prop in React?](#what-is-the-purpose-of-the-children-prop-in-react)                                                                                                                         |
| 37  | [Explain the concept of useRef() hook in React?](#explain-the-concept-of-useref-hook-in-react)                                                                                                                                   |
| 38  | [What are the benefits of using React's strict mode?](#what-are-the-benefits-of-using-reacts-strict-mode)                                                                                                                        |
                                 
</details>


---
<br>

## React Questions

<br>

1.  ### What is React?

    React (aka React.js or ReactJS) is an **open-source front-end JavaScript library** that is used for building composable user interfaces, especially for single-page applications. It is used for handling view layer for web and mobile apps based on components in a declarative approach. 
    
    React was created by [Jordan Walke](https://github.com/jordwalke), a software engineer working for Facebook. React was first deployed on Facebook's News Feed in 2011 and on Instagram in 2012.

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>


2. ### What is the history behind React evolution?
    The history of ReactJS started in 2010 with the creation of **XHP**. XHP is a PHP extension which improved the syntax of the language such that XML document fragments become valid PHP expressions and the primary purpose was used to create custom and reusable HTML elements. 
    
    The main principle of this extension was to make front-end code easier to understand and to help avoid cross-site scripting attacks. The project was successful to prevent the malicious content submitted by the scrubbing user.

    But there was a different problem with XHP in which dynamic web applications require many roundtrips to the server, and XHP did not solve this problem. Also, the whole UI was re-rendered for small change in the application. Later, the initial prototype of React is created with the name **FaxJ** by Jordan inspired from XHP. Finally after sometime React has been introduced as a new library into JavaScript world.

    **Note:** JSX comes from the idea of XHP

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
   
    
3.  ### What are the major features of React?

    The major features of React are:

    - Uses **JSX** syntax, a syntax extension of JS that allows developers to write HTML in their JS code.
    - It uses **Virtual DOM** instead of Real DOM considering that Real DOM manipulations are expensive.
    - Supports **server-side rendering** which is useful for Search Engine Optimizations(SEO).
    - Follows **Unidirectional or one-way** data flow or data binding.
    - Uses **reusable/composable** UI components to develop the view.

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    
    
4. ### What is JSX in React?
   
     JSX (JavaScript XML) is a syntax extension for JavaScript used in React to describe the structure of UI components. It allows developers to write HTML-like code directly in JavaScript. JSX is compiled into regular JavaScript functions by tools like Babel before being executed by the browser.

   ```jsx harmony
     import React from 'react';
     import ReactDOM from 'react-dom';
     
     const App = () => {
         return (
             <div>
                 <h1>Hello, World!</h1>
                 <p>This is a JSX example.</p>
             </div>
         );
     };
     
     ReactDOM.render(<App />, document.getElementById('root'));
   ```
   
     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    

5. ### What are state and props in React?
   
     State is an internal data storage mechanism in React components, managed by React itself. Props (short for properties) are read-only data passed from parent to child components. The main difference is that state is mutable and controlled by the component itself, whereas props are immutable and controlled by the parent component.

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    

6. ### What is the significance of keys in React lists?

   Keys are special string attributes used by React to identify which items have changed, been added, or been removed in a list of elements. Keys help React efficiently update the UI by minimizing re-renders. Keys should be unique among siblings, but don't need to be globally unique.

   ```jsx harmony
     const ListComponent = () => {
         const items = ['apple', 'banana', 'cherry'];
     
         return (
             <ul>
                 {items.map((item, index) => (
                     <li key={index}>{item}</li>
                 ))}
             </ul>
         );
     };
   ```

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    
          
7. ### Explain the component lifecycle methods in React?
   
     React components have several lifecycle methods that execute at different stages of a component's existence. These methods include `componentDidMount`, `componentDidUpdate`, `componentWillUnmount`, etc. They allow developers to hook into different points in a component's lifecycle to perform tasks like fetching data, updating the DOM, or cleaning up resources.

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    
   
8. ### What is the significance of setState in React?
   
     `setState()` is a method used to update the state of a React component. When `setState()` is called, React re-renders the component and its children. It can take an object as an argument to update state properties asynchronously, or a callback function to perform actions after the state has been updated.

     ```jsx harmony
          import React, { Component } from 'react';
          
          class Counter extends Component {
              constructor(props) {
                  super(props);
                  this.state = {
                      count: 0
                  };
              }
          
              incrementCount = () => {
                  this.setState({ count: this.state.count + 1 });
              };
          
              render() {
                  return (
                      <div>
                          <p>Count: {this.state.count}</p>
                          <button onClick={this.incrementCount}>Increment</button>
                      </div>
                  );
              }
          }
          
          export default Counter;
     ```

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    
   
9. ### Explain the concept of higher-order components in React?
    
     Higher-order components are functions that take a component and return a new component with enhanced functionality. They are a common pattern for code reuse, logic sharing, and cross-cutting concerns like authentication, logging, etc. HOCs allow you to abstract away common logic into reusable functions.

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    
   
10. ### What are controlled components in React?
    
     Controlled components are components whose form elements (like inputs, selects, and textareas) are controlled by React state. This means that the component renders a form element whose value is controlled by React, and React handles the value changes through state and event handlers.

    ```jsx harmony
     import React, { Component } from 'react';
     
     class ControlledComponent extends Component {
         constructor(props) {
             super(props);
             this.state = {
                 value: ''
             };
         }
     
         handleChange = (event) => {
             this.setState({ value: event.target.value });
         };
     
         render() {
             return (
                 <input
                     type="text"
                     value={this.state.value}
                     onChange={this.handleChange}
                 />
             );
         }
     }
     
     export default ControlledComponent;
    ```

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    
    
11. ### Explain the difference between functional components and class components in React?

    Functional components are JavaScript functions that accept props and return React elements. They are simpler and more lightweight than class components, and they can use React hooks to manage state and lifecycle.  <br>
    Class components are ES6 classes that extend `React.Component` and have their own state and lifecycle methods.

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    
    
12. ### What are React hooks?

     React hooks are functions that allow functional components to use state, lifecycle, and other React features without writing a class. Examples of hooks include `useState`, `useEffect`, `useContext`, etc. Custom hooks are functions that use hooks internally and allow you to reuse stateful logic between different components.

     ```jsx harmony
          import { useState } from 'react';
          
          const useCounter = (initialCount) => {
              const [count, setCount] = useState(initialCount);
          
              const increment = () => {
                  setCount(count + 1);
              };
          
              return { count, increment };
          };
          
          export default useCounter;
     ```

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    
    
13. ### What are React Fragments?

     React Fragments allow you to group multiple children elements without adding extra nodes to the DOM. They are useful when you need to return multiple elements from a component's render method, but don't want to add unnecessary divs or spans. Fragments improve code readability and performance by reducing the number of DOM elements.

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    

14. ### What are refs in React?
    
     Refs in React provide a way to access the underlying DOM nodes or React elements directly. They are primarily used for managing focus, integrating with third-party DOM libraries, or triggering imperative animations.

      ```jsx harmony
          import React, { useRef } from 'react';
          
          const RefExample = () => {
              const inputRef = useRef(null);
          
              const focusInput = () => {
                  inputRef.current.focus();
              };
          
              return (
                  <div>
                      <input ref={inputRef} type="text" />
                      <button onClick={focusInput}>Focus Input</button>
                  </div>
              );
          };
          
          export default RefExample;
     ```

     **[⬆ Back to Top](#table-of-contents)**
      <br><br>
      
 
15. ### What is context in React?

     Context in React provides a way to pass data through the component tree without having to pass props manually at every level. It's primarily used when some data needs to be accessible by many components at different nesting levels.

     ```jsx harmony
          import React, { createContext, useContext } from 'react';
          
          const ThemeContext = createContext('light');
          
          const ThemedComponent = () => {
              const theme = useContext(ThemeContext);
              return <p>Current Theme: {theme}</p>;
          };
          
          const ContextExample = () => {
              return (
                  <ThemeContext.Provider value="dark">
                      <ThemedComponent />
                  </ThemeContext.Provider>
              );
          };
          
          export default ContextExample;
     ```
     
     **[⬆ Back to Top](#table-of-contents)**
       <br><br>
       
 
16. ### Explain the concept of virtual DOM in React?
    
     The virtual DOM in React is a lightweight copy of the actual DOM maintained by React. When state or props change, React compares the virtual DOM with the previous version and computes the minimum number of DOM operations needed to update the actual DOM. This process makes React applications more efficient by minimizing DOM manipulation. <br> <br>
    **Another Example:** <br>
     Imagine you have a list of items in your UI, and you update one item's text. Instead of directly manipulating the DOM to change the text, React updates the virtual DOM, compares it with the previous state, and efficiently applies the necessary changes to the actual DOM.

     **[⬆ Back to Top](#table-of-contents)**
        <br><br>
        
    
17. ### What are keys and why are they important in React lists?
    
     Keys are special attributes used by React to identify which items have changed, been added, or been removed in a list of elements. They help React efficiently update the UI by minimizing re-renders and ensuring that elements are re-used properly. Keys should be unique among siblings, but don't need to be globally unique. <br> <br>
    **Another Example:** <br>
     Consider rendering a list of items dynamically using map(). Assigning a unique key to each item allows React to track which items have been added, removed, or updated efficiently.

     **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    
    
18. ### What are the differences between useState and useReducer hooks in React?
    
     Both `useState` and `useReducer` hooks are used to manage state in functional components. The main difference is that `useState` is simpler and more suitable for managing independent state variables, while `useReducer` is more powerful and allows for complex state logic and actions.

     ```jsx harmony
          import React, { useReducer } from 'react';
          
          const initialState = { count: 0 };
          
          const reducer = (state, action) => {
              switch (action.type) {
                  case 'increment':
                      return { count: state.count + 1 };
                  case 'decrement':
                      return { count: state.count - 1 };
                  default:
                      return state;
              }
          };
          
          const ReducerExample = () => {
              const [state, dispatch] = useReducer(reducer, initialState);
          
              return (
                  <div>
                      Count: {state.count}
                      <button onClick={() => dispatch({ type: 'increment' })}>Increment</button>
                      <button onClick={() => dispatch({ type: 'decrement' })}>Decrement</button>
                  </div>
              );
          };
          
          export default ReducerExample;
     ```

      **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    

19. ### Explain the concept of lazy loading in React?
    
     Lazy loading is a technique used to defer the loading of non-essential resources (such as components or data) until they are actually needed. In React, lazy loading can be achieved using dynamic imports and the `React.lazy()` function, which allows you to import components asynchronously.

     ```jsx harmony
          import React, { Suspense } from 'react';
          
          const LazyLoadedComponent = React.lazy(() => import('./LazyLoadedComponent'));
          
          const LazyLoadingExample = () => (
              <Suspense fallback={<div>Loading...</div>}>
                  <LazyLoadedComponent />
              </Suspense>
          );
          
          export default LazyLoadingExample;
     ```

      **[⬆ Back to Top](#table-of-contents)**
    <br><br>
    
20. ### What are the benefits of using PropTypes in React?
    
     PropTypes is a runtime type checking mechanism for React props. It helps catch bugs early by providing a way to specify the type of each prop a component should receive. PropTypes also serve as documentation for components, making it easier for other developers to understand how to use them.

     ```jsx harmony
          import React from 'react';
          import PropTypes from 'prop-types';
          
          const MyComponent = ({ name, age }) => (
              <div>
                  <p>Name: {name}</p>
                  <p>Age: {age}</p>
              </div>
          );
          
          MyComponent.propTypes = {
              name: PropTypes.string.isRequired,
              age: PropTypes.number.isRequired
          };
          
          export default MyComponent;
     ```

      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

    
21. ### What are React hooks? Can you name a few built-in hooks and explain their use cases?
    
     React hooks are functions that enable functional components to use state and lifecycle features without writing a class. Some built-in hooks include `useState` for managing state, `useEffect` for handling side effects, `useContext` for accessing context, and `useReducer` for managing more complex state logic.

     ```jsx harmony
          import React, { useState, useEffect } from 'react';
          
          const HooksExample = () => {
              const [count, setCount] = useState(0);
          
              useEffect(() => {
                  document.title = `You clicked ${count} times`;
              }, [count]);
          
              return (
                  <div>
                      <p>You clicked {count} times</p>
                      <button onClick={() => setCount(count + 1)}>
                          Click me
                      </button>
                  </div>
              );
          };
          
          export default HooksExample;
     ```

      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

    
22. ### Explain the concept of conditional rendering in React?

     Conditional rendering is the process of dynamically determining whether a component or element should be rendered based on certain conditions. This is typically done using JavaScript expressions or ternary operators inside JSX.

     ```jsx harmony
          import React from 'react';
          
          const ConditionalComponent = ({ isLoggedIn }) => {
              return isLoggedIn ? <p>Welcome, User!</p> : <p>Please log in.</p>;
          };
          
          export default ConditionalComponent;
     ```
     
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

    
23. ### What are the advantages of using arrow functions in React event handlers?
    
     Arrow functions automatically bind `this` to the enclosing lexical scope, which eliminates the need to manually bind `this` in event handlers. This makes the code cleaner and more concise, especially when dealing with complex component hierarchies or passing functions as props.

     ```jsx harmony
          import React, { useState } from 'react';
          
          const ArrowFunctionExample = () => {
              const [count, setCount] = useState(0);
          
              const handleClick = () => {
                  setCount(count + 1);
              };
          
              return (
                  <div>
                      <p>Count: {count}</p>
                      <button onClick={handleClick}>Increment</button>
                  </div>
              );
          };

          export default ArrowFunctionExample;
     ```
     
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

    
24. ### What is the purpose of useEffect hook in React? How does it differ from componentDidMount and componentDidUpdate lifecycle methods?

     The `useEffect` hook in React is used to perform side effects in functional components. It combines the functionality of `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount` lifecycle methods in class components. It's called after every render and allows you to perform data fetching, subscriptions, or manually changing the DOM.

     ```jsx
         import React, { useState, useEffect } from 'react';
     
         const EffectExample = () => {
             const [count, setCount] = useState(0);
     
             useEffect(() => {
                 document.title = `You clicked ${count} times`;
             }, [count]);
     
             return (
                 <div>
                     <p>You clicked {count} times</p>
                     <button onClick={() => setCount(count + 1)}>
                         Click me
                     </button>
                 </div>
             );
         };
     
         export default EffectExample;
     ```
          
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

  
25. ### What are React portals?

     React portals provide a way to render children into a DOM node that exists outside the DOM hierarchy of the parent component. This is useful for scenarios like modals, tooltips, or dropdown menus where you want to render content at a different location in the DOM tree.

     ```jsx
         import React, { useState } from 'react';
         import ReactDOM from 'react-dom';
     
         const PortalExample = () => {
             const [showModal, setShowModal] = useState(false);
     
             return (
                 <div>
                     <button onClick={() => setShowModal(true)}>Open Modal</button>
                     {showModal &&
                         ReactDOM.createPortal(
                             <div className="modal">
                                 <div className="modal-content">
                                     <span className="close" onClick={() => setShowModal(false)}>
                                         &times;
                                     </span>
                                     <p>This is a modal</p>
                                 </div>
                             </div>,
                             document.getElementById('modal-root')
                         )}
                 </div>
             );
         };
     
         export default PortalExample;
     ```
          
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

  
26. ### What is the purpose of React Router?

     React Router is a library that allows you to handle routing in React applications. It provides components like `BrowserRouter`, `Route`, `Link`, etc., for declarative routing. React Router enables navigation between different components/pages of a single-page application.

     ```jsx
         import React from 'react';
         import { BrowserRouter as Router, Route, Link } from 'react-router-dom';
     
         const Home = () => <h2>Home</h2>;
         const About = () => <h2>About</h2>;
     
         const RoutingExample = () => (
             <Router>
                 <div>
                     <nav>
                         <ul>
                             <li>
                                 <Link to="/">Home</Link>
                             </li>
                             <li>
                                 <Link to="/about">About</Link>
                             </li>
                         </ul>
                     </nav>
                     <Route path="/" exact component={Home} />
                     <Route path="/about" component={About} />
                 </div>
             </Router>
         );
     
         export default RoutingExample;
     ```
          
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

  
27. ### Explain the concept of error boundaries in React?

     Error boundaries in React are components that catch JavaScript errors anywhere in their child component tree, log those errors, and display a fallback UI instead of crashing the entire application. Error boundaries are useful for handling errors in components with asynchronous code, third-party libraries, or complex UI logic.

     ```jsx
         import React, { Component } from 'react';
     
         class ErrorBoundary extends Component {
             constructor(props) {
                 super(props);
                 this.state = { hasError: false };
             }
     
             static getDerivedStateFromError(error) {
                 return { hasError: true };
             }
     
             componentDidCatch(error, errorInfo) {
                 console.error('Error:', error);
                 console.error('Error Info:', errorInfo);
             }
     
             render() {
                 if (this.state.hasError) {
                     return <h1>Something went wrong.</h1>;
                 }
                 return this.props.children;
             }
         }
     
         export default ErrorBoundary;
     ```
          
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

  
28. ### What are controlled and uncontrolled components in React?

     Controlled components are components whose form elements (like inputs, selects, and textareas) are controlled by React state. Uncontrolled components are components whose form elements are not controlled by React state but instead rely on the DOM to manage their state.

     ```jsx
         // Controlled Component
         import React, { useState } from 'react';
     
         const ControlledComponent = () => {
             const [value, setValue] = useState('');
     
             const handleChange = (event) => {
                 setValue(event.target.value);
             };
     
             return (
                 <input
                     type="text"
                     value={value}
                     onChange={handleChange}
                 />
             );
         };
     
         export default ControlledComponent;
    ```

    ```jsx
         // Uncontrolled Component
         import React from 'react';
     
         const UncontrolledComponent = () => (
             <input
                 type="text"
                 defaultValue="Initial Value"
             />
         );
     
         export default UncontrolledComponent;
    ```
         
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

  
29. ### What is the purpose of memo in React?

     The `memo` function in React is a higher-order component that memoizes the result of a functional component rendering. It's similar to `PureComponent` for class components and prevents unnecessary re-renders by caching the result of the component's render method.

      ```jsx
         import React, { memo } from 'react';
     
         const MemoizedComponent = memo(({ name }) => {
             console.log('Rendering MemoizedComponent');
             return <p>Hello, {name}!</p>;
         });
     
         export default MemoizedComponent;
    ```
           
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

  
30. ### What is server-side rendering (SSR) in React? How does it differ from client-side rendering (CSR)?

     Server-side rendering (SSR) is the process of rendering React components on the server and sending the generated HTML to the client. This allows search engines and social media crawlers to index the content and improves performance by reducing the time to first meaningful paint. Client-side rendering (CSR), on the other hand, renders React components in the browser using JavaScript. <br>

     In SSR, the initial HTML content is sent from the server to the client, which can improve SEO and reduce time to content for users. CSR, on the other hand, sends a minimal HTML file with JavaScript, which then fetches and renders the content in the browser.
     
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>

  
31. ### Explain the concept of code splitting in React?

     Code splitting is a technique used to split your code into smaller bundles that can be loaded on demand. This helps reduce the initial bundle size and improve performance by only loading the code that is necessary for the current route or feature. In React, code splitting can be implemented using dynamic imports or `React.lazy()` for components.

     ```jsx
         import React, { lazy, Suspense } from 'react';
     
         const LazyLoadedComponent = lazy(() => import('./LazyLoadedComponent'));
     
         const CodeSplittingExample = () => (
             <Suspense fallback={<div>Loading...</div>}>
                 <LazyLoadedComponent />
             </Suspense>
         );
     
         export default CodeSplittingExample;
    ```
          
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>


32. ### Explain the concept of React Suspense?

     React Suspense is a feature that allows components to suspend rendering while waiting for some asynchronous data to load. It's used to create better loading experiences in React applications by showing fallback UIs while waiting for data to fetch. <br>

     Suspense is often used in conjunction with React.lazy() for lazy loading components and React Concurrent Mode for handling concurrent rendering.
             
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>


33. ### What are the benefits of using React hooks over class components?

     React hooks simplify state management and lifecycle management in functional components, making them easier to read and write. Hooks encourage code reuse and better encapsulation of logic. They also enable functional components to have their own state and lifecycle methods, eliminating the need for class components in most cases.
             
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>


34. ### Explain the concept of memoization in React?

     Memoization is a technique used to optimize performance by storing the results of expensive function calls and returning the cached result when the same inputs occur again. In React, memoization can be achieved using the `React.memo()` higher-order component or the `useMemo()` hook to memoize the result of a computation.
             
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>


35. ### What are the differences between React's setState() and useState() hooks?

     `setState()` is a method used to update the state of a React component in class components, while `useState()` is a hook used to manage state in functional components. `setState()` allows you to update multiple state properties at once and provides a callback function for performing actions after the state has been updated, while `useState()` returns a single state variable and a function to update it.
             
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>


36. ### What is the purpose of the children prop in React?

     The `children` prop in React is a special prop that allows components to accept arbitrary JSX as children. It's useful for creating reusable components that can wrap other components or elements.

    ```jsx
         import React from 'react';
     
         const WrapperComponent = ({ children }) => (
             <div className="wrapper">
                 {children}
             </div>
         );
     
         export default WrapperComponent;
    ```
             
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>


37. ### Explain the concept of useRef() hook in React?

     The `useRef()` hook in React returns a mutable ref object whose `.current` property is initialized to the passed argument (initialValue). It's primarily used to access DOM nodes or React elements directly, or to persist values between renders without causing re-renders.

     ```jsx
         import React, { useRef } from 'react';
     
         const InputWithFocus = () => {
             const inputRef = useRef();
     
             const focusInput = () => {
                 inputRef.current.focus();
             };
     
             return (
                 <div>
                     <input ref={inputRef} type="text" />
                     <button onClick={focusInput}>Focus Input</button>
                 </div>
             );
         };
     
         export default InputWithFocus;
    ```
              
      **[⬆ Back to Top](#table-of-contents)**
    <br><br>


38. ### What are the benefits of using React's strict mode?

     React's strict mode is a feature that helps detect potential problems in your code by highlighting unsafe lifecycles, legacy string ref usage, and more. It's used to identify and fix common mistakes in React applications. Strict mode can be enabled by wrapping your application in a `<React.StrictMode>` component or adding `{ strictMode: true }` to the ReactDOM.render options.





---

## Disclaimer

The questions provided in this repository are the summary of frequently asked questions across numerous companies. We cannot guarantee that these questions will actually be asked during your interview process, nor should you focus on memorizing all of them. The primary purpose is for you to get a sense of what some companies might ask — do not get discouraged if you don't know the answer to all of them ⁠— that is ok!

Good luck with your interview 😊

---

