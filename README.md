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
|     | **Core React**                                                                                                                                                                                                                   |
| 1   | [What is React?](#what-is-react)                                                                                                                                                                                                 |
| 2   | [What is the history behind React evolution?](#What-is-the-history-behind-react-evolution)                                                                                                                                       |
| 3   | [What are the major features of React?](#what-are-the-major-features-of-react)                                                                                                                                                   |
| 4   | [What is JSX in React?](#what-is-jsx-in-react)                                                                                                                                                                                   |
| 5   | [What are state and props in React?](#what-are-state-and-props-in-react)                                                                                                                                                         |
| 6   | [What is the significance of keys in React lists?](#what-is-the-significance-of-keys-in-react-lists)                                                                                                                             |
| 7   | [Explain the component lifecycle methods in React?](#explain-the-component-lifecycle-methods-in-react)                                                                                                                           |
| 8   | [What is the significance of setState in React?](#what-is-the-significance-of-setState-in-react)                                                                                                                               |
| 9   | [Explain the concept of higher-order components in React?](#explain-the-concept-of-higher-order-components-in-react)                                                                                                             |
| 10  | [What are controlled components in React?](#what-are-controlled-components-in-react)                                                                                                                                             |
| 11  | [Explain the difference between functional components and class components in React?](#explain-the-difference-between-functional-components-and-class-components-in-react)                                                       |
| 12  | [What are React hooks?](#what-are-react-hooks)                                                                                                                                                                                   |
| 13  | [What are React Fragments?](#what-are-react-fragments)                                                                                                                                                                           |
                                 
</details>


---

## Core React

1.  ### What is React?

    React (aka React.js or ReactJS) is an **open-source front-end JavaScript library** that is used for building composable user interfaces, especially for single-page applications. It is used for handling view layer for web and mobile apps based on components in a declarative approach. 
    
    React was created by [Jordan Walke](https://github.com/jordwalke), a software engineer working for Facebook. React was first deployed on Facebook's News Feed in 2011 and on Instagram in 2012.

     **[⬆ Back to Top](#table-of-contents)**
    

2. ### What is the history behind React evolution?
    The history of ReactJS started in 2010 with the creation of **XHP**. XHP is a PHP extension which improved the syntax of the language such that XML document fragments become valid PHP expressions and the primary purpose was used to create custom and reusable HTML elements. 
    
    The main principle of this extension was to make front-end code easier to understand and to help avoid cross-site scripting attacks. The project was successful to prevent the malicious content submitted by the scrubbing user.

    But there was a different problem with XHP in which dynamic web applications require many roundtrips to the server, and XHP did not solve this problem. Also, the whole UI was re-rendered for small change in the application. Later, the initial prototype of React is created with the name **FaxJ** by Jordan inspired from XHP. Finally after sometime React has been introduced as a new library into JavaScript world.

    **Note:** JSX comes from the idea of XHP

     **[⬆ Back to Top](#table-of-contents)**
   
    
3.  ### What are the major features of React?

    The major features of React are:

    - Uses **JSX** syntax, a syntax extension of JS that allows developers to write HTML in their JS code.
    - It uses **Virtual DOM** instead of Real DOM considering that Real DOM manipulations are expensive.
    - Supports **server-side rendering** which is useful for Search Engine Optimizations(SEO).
    - Follows **Unidirectional or one-way** data flow or data binding.
    - Uses **reusable/composable** UI components to develop the view.

     **[⬆ Back to Top](#table-of-contents)**

    
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


5. ### What are state and props in React?
   
     State is an internal data storage mechanism in React components, managed by React itself. Props (short for properties) are read-only data passed from parent to child components. The main difference is that state is mutable and controlled by the component itself, whereas props are immutable and controlled by the parent component.

     **[⬆ Back to Top](#table-of-contents)**


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

          
7. ### Explain the component lifecycle methods in React?
   
     React components have several lifecycle methods that execute at different stages of a component's existence. These methods include componentDidMount, componentDidUpdate, componentWillUnmount, etc. They allow developers to hook into different points in a component's lifecycle to perform tasks like fetching data, updating the DOM, or cleaning up resources.

     **[⬆ Back to Top](#table-of-contents)**

   
8. ### What is the significance of setState in React?
   
     setState() is a method used to update the state of a React component. When setState() is called, React re-renders the component and its children. It can take an object as an argument to update state properties asynchronously, or a callback function to perform actions after the state has been updated.

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

   
9. ### Explain the concept of higher-order components in React?
    
     Higher-order components are functions that take a component and return a new component with enhanced functionality. They are a common pattern for code reuse, logic sharing, and cross-cutting concerns like authentication, logging, etc. HOCs allow you to abstract away common logic into reusable functions.

     **[⬆ Back to Top](#table-of-contents)**

   
10. ### What are controlled components in React?
    
     Controlled components are components whose form elements (like inputs, selects, and textareas) are controlled by React state. This means that the component renders a form element whose value is controlled by React, and React handles the value changes through state and event handlers.Example:

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

    
11. ### Explain the difference between functional components and class components in React?

    Functional components are JavaScript functions that accept props and return React elements. They are simpler and more lightweight than class components, and they can use React hooks to manage state and lifecycle.    
    Class components are ES6 classes that extend React.Component and have their own state and lifecycle methods.

     **[⬆ Back to Top](#table-of-contents)**

    
12. ### What are React hooks?

     React hooks are functions that allow functional components to use state, lifecycle, and other React features without writing a class. Examples of hooks include useState, useEffect, useContext, etc. Custom hooks are functions that use hooks internally and allow you to reuse stateful logic between different components.

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

    
13. ### What are React Fragments?

     React Fragments allow you to group multiple children elements without adding extra nodes to the DOM. They are useful when you need to return multiple elements from a component's render method, but don't want to add unnecessary divs or spans. Fragments improve code readability and performance by reducing the number of DOM elements.

     **[⬆ Back to Top](#table-of-contents)**





---

## Disclaimer

The questions provided in this repository are the summary of frequently asked questions across numerous companies. We cannot guarantee that these questions will actually be asked during your interview process, nor should you focus on memorizing all of them. The primary purpose is for you to get a sense of what some companies might ask — do not get discouraged if you don't know the answer to all of them ⁠— that is ok!

Good luck with your interview 😊

---

