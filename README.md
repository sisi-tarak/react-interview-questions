# ReactJS Interview Questions & Answers

> Click ⭐ if you like the project. Follow me [@sisi_tarakk](https://www.instagram.com/sisi_tarakk) on Instagram and [@sisitarak](https://www.linkedin.com/in/sisitarak) on LinkedIn for more.

> Pull Requests are highly recommended and appreciated. 🙌

---

### Table of Contents

<details open>
<summary>
Hide/Show table of contents
</summary>

#### 🟢 Basic Level

| No. | Questions |
| --- | --------- |
| 1 | [What is React?](#1-what-is-react) |
| 2 | [What is the history behind React evolution?](#2-what-is-the-history-behind-react-evolution) |
| 3 | [What are the major features of React?](#3-what-are-the-major-features-of-react) |
| 4 | [What is JSX in React?](#4-what-is-jsx-in-react) |
| 5 | [What are the differences between Real DOM and Virtual DOM?](#5-what-are-the-differences-between-real-dom-and-virtual-dom) |
| 6 | [What are components in React?](#6-what-are-components-in-react) |
| 7 | [What is the difference between functional and class components?](#7-what-is-the-difference-between-functional-and-class-components) |
| 8 | [What are props in React?](#8-what-are-props-in-react) |
| 9 | [What is state in React?](#9-what-is-state-in-react) |
| 10 | [What is the difference between state and props?](#10-what-is-the-difference-between-state-and-props) |
| 11 | [What are the significance of keys in React lists?](#11-what-is-the-significance-of-keys-in-react-lists) |
| 12 | [What is conditional rendering in React?](#12-what-is-conditional-rendering-in-react) |
| 13 | [How do you render a list in React?](#13-how-do-you-render-a-list-in-react) |
| 14 | [What are React Fragments?](#14-what-are-react-fragments) |
| 15 | [What are controlled components?](#15-what-are-controlled-components) |
| 16 | [What are uncontrolled components?](#16-what-are-uncontrolled-components) |
| 17 | [What is the significance of setState in React?](#17-what-is-the-significance-of-setstate-in-react) |
| 18 | [What are default props?](#18-what-are-default-props) |
| 19 | [What is prop drilling?](#19-what-is-prop-drilling) |
| 20 | [What are React events? How are they different from HTML events?](#20-what-are-react-events-how-are-they-different-from-html-events) |
| 21 | [What is the children prop?](#21-what-is-the-children-prop) |
| 22 | [What is the purpose of React.StrictMode?](#22-what-is-the-purpose-of-reactstrictmode) |
| 23 | [What are PropTypes in React?](#23-what-are-proptypes-in-react) |
| 24 | [How do you add inline styles in React?](#24-how-do-you-add-inline-styles-in-react) |
| 25 | [What is create-react-app? Is it still relevant?](#25-what-is-create-react-app-is-it-still-relevant) |

#### 🟡 Medium Level — React Hooks

| No. | Questions |
| --- | --------- |
| 26 | [What are React Hooks? Why were they introduced?](#26-what-are-react-hooks-why-were-they-introduced) |
| 27 | [Explain useState hook in detail](#27-explain-usestate-hook-in-detail) |
| 28 | [Explain useEffect hook and all its dependency cases](#28-explain-useeffect-hook-and-all-its-dependency-cases) |
| 29 | [Explain useRef hook and its use cases](#29-explain-useref-hook-and-its-use-cases) |
| 30 | [Explain useContext hook](#30-explain-usecontext-hook) |
| 31 | [Explain useReducer hook](#31-explain-usereducer-hook) |
| 32 | [Explain useMemo hook](#32-explain-usememo-hook) |
| 33 | [Explain useCallback hook](#33-explain-usecallback-hook) |
| 34 | [What is the difference between useMemo and useCallback?](#34-what-is-the-difference-between-usememo-and-usecallback) |
| 35 | [What are custom hooks? Write an example](#35-what-are-custom-hooks-write-an-example) |
| 36 | [What is useLayoutEffect? How is it different from useEffect?](#36-what-is-uselayouteffect-how-is-it-different-from-useeffect) |
| 37 | [What is useId hook (React 18)?](#37-what-is-useid-hook-react-18) |
| 38 | [What is useTransition hook?](#38-what-is-usetransition-hook) |
| 39 | [What is useDeferredValue hook?](#39-what-is-usedeferredvalue-hook) |

#### 🟡 Medium Level — Component Patterns & Lifecycle

| No. | Questions |
| --- | --------- |
| 40 | [What are the lifecycle methods in a class component?](#40-what-are-the-lifecycle-methods-in-a-class-component) |
| 41 | [What is the component lifecycle in functional components?](#41-what-is-the-component-lifecycle-in-functional-components) |
| 42 | [What is React.memo?](#42-what-is-reactmemo) |
| 43 | [What are Higher-Order Components (HOC)?](#43-what-are-higher-order-components-hoc) |
| 44 | [What is the Render Props pattern?](#44-what-is-the-render-props-pattern) |
| 45 | [What are React Portals?](#45-what-are-react-portals) |
| 46 | [What are Error Boundaries?](#46-what-are-error-boundaries) |
| 47 | [What is the Context API?](#47-what-is-the-context-api) |
| 48 | [What is lazy loading in React?](#48-what-is-lazy-loading-in-react) |
| 49 | [What is React Suspense?](#49-what-is-react-suspense) |
| 50 | [What is code splitting?](#50-what-is-code-splitting) |
| 51 | [What is forwardRef in React?](#51-what-is-forwardref-in-react) |
| 52 | [What is reconciliation in React?](#52-what-is-reconciliation-in-react) |
| 53 | [What is lifting state up?](#53-what-is-lifting-state-up) |

#### 🟡 Medium Level — React Router

| No. | Questions |
| --- | --------- |
| 54 | [What is React Router and why is it used?](#54-what-is-react-router-and-why-is-it-used) |
| 55 | [What are the core components of React Router v6?](#55-what-are-the-core-components-of-react-router-v6) |
| 56 | [Explain the difference between BrowserRouter and HashRouter](#56-explain-the-difference-between-browserrouter-and-hashrouter) |
| 57 | [How do you define routes in React Router?](#57-how-do-you-define-routes-in-react-router) |
| 58 | [How do you pass and access URL parameters using React Router?](#58-how-do-you-pass-and-access-url-parameters-using-react-router) |
| 59 | [What is nested routing in React Router?](#59-what-is-nested-routing-in-react-router) |
| 60 | [How do you implement programmatic navigation?](#60-how-do-you-implement-programmatic-navigation) |
| 61 | [How do you handle protected routes in React Router?](#61-how-do-you-handle-protected-routes-in-react-router) |
| 62 | [How do you handle query parameters in React Router?](#62-how-do-you-handle-query-parameters-in-react-router) |

#### 🔴 Advanced Level — State Management

| No. | Questions |
| --- | --------- |
| 63 | [What is Redux? Explain its core concepts](#63-what-is-redux-explain-its-core-concepts) |
| 64 | [Explain the data flow in a Redux application](#64-explain-the-data-flow-in-a-redux-application) |
| 65 | [What is Redux Toolkit? Why is it preferred over vanilla Redux?](#65-what-is-redux-toolkit-why-is-it-preferred-over-vanilla-redux) |
| 66 | [How do you handle async operations in Redux?](#66-how-do-you-handle-async-operations-in-redux) |
| 67 | [What is Zustand? How does it compare to Redux?](#67-what-is-zustand-how-does-it-compare-to-redux) |
| 68 | [What is the difference between client state and server state?](#68-what-is-the-difference-between-client-state-and-server-state) |
| 69 | [What is React Query (TanStack Query)?](#69-what-is-react-query-tanstack-query) |

#### 🔴 Advanced Level — Performance & Architecture

| No. | Questions |
| --- | --------- |
| 70 | [What is React Fiber?](#70-what-is-react-fiber) |
| 71 | [What is the difference between the Render Phase and Commit Phase?](#71-what-is-the-difference-between-the-render-phase-and-commit-phase) |
| 72 | [How do you prevent unnecessary re-renders?](#72-how-do-you-prevent-unnecessary-re-renders) |
| 73 | [What is state colocation?](#73-what-is-state-colocation) |
| 74 | [How do you optimize a large list (1000+ items) in React?](#74-how-do-you-optimize-a-large-list-1000-items-in-react) |
| 75 | [What are common React performance anti-patterns?](#75-what-are-common-react-performance-anti-patterns) |
| 76 | [What is the Compound Component pattern?](#76-what-is-the-compound-component-pattern) |
| 77 | [What is SSR in React? How is it different from CSR?](#77-what-is-ssr-in-react-how-is-it-different-from-csr) |
| 78 | [What is Next.js? Why is it used with React?](#78-what-is-nextjs-why-is-it-used-with-react) |
| 79 | [What are React Server Components (RSC)?](#79-what-are-react-server-components-rsc) |
| 80 | [What is Concurrent Mode in React 18?](#80-what-is-concurrent-mode-in-react-18) |
| 81 | [What is automatic batching in React 18?](#81-what-is-automatic-batching-in-react-18) |

#### 🔴 Advanced Level — Testing & Security

| No. | Questions |
| --- | --------- |
| 82 | [How do you test React components?](#82-how-do-you-test-react-components) |
| 83 | [What is React Testing Library and how is it different from Enzyme?](#83-what-is-react-testing-library-and-how-is-it-different-from-enzyme) |
| 84 | [What is the act() utility in testing?](#84-what-is-the-act-utility-in-testing) |
| 85 | [What are common security concerns in React apps?](#85-what-are-common-security-concerns-in-react-apps) |
| 86 | [What is XSS and how do you prevent it in React?](#86-what-is-xss-and-how-do-you-prevent-it-in-react) |

#### 🔴 Advanced Level — React 19 & Future

| No. | Questions |
| --- | --------- |
| 87 | [What are the new features in React 19?](#87-what-are-the-new-features-in-react-19) |
| 88 | [What is the React Compiler?](#88-what-is-the-react-compiler) |
| 89 | [What is useOptimistic hook?](#89-what-is-useoptimistic-hook) |
| 90 | [What are Server Actions in React 19?](#90-what-are-server-actions-in-react-19) |

#### 🎯 Scenario & Conceptual Questions (MNC Favourites)

| No. | Questions |
| --- | --------- |
| 91 | [When would you use useReducer over useState?](#91-when-would-you-use-usereducer-over-usestate) |
| 92 | [When would you use Context API vs Redux?](#92-when-would-you-use-context-api-vs-redux) |
| 93 | [How would you handle forms in a large React application?](#93-how-would-you-handle-forms-in-a-large-react-application) |
| 94 | [How do you architect a large-scale React application?](#94-how-do-you-architect-a-large-scale-react-application) |
| 95 | [How do you implement authentication in a React app?](#95-how-do-you-implement-authentication-in-a-react-app) |
| 96 | [What happens when you call setState inside useEffect?](#96-what-happens-when-you-call-setstate-inside-useeffect) |
| 97 | [Why should you not update state directly in React?](#97-why-should-you-not-update-state-directly-in-react) |
| 98 | [What is derived state? Why should you avoid storing it in state?](#98-what-is-derived-state-why-should-you-avoid-storing-it-in-state) |
| 99 | [How does React handle accessibility (a11y)?](#99-how-does-react-handle-accessibility-a11y) |
| 100 | [Explain tree shaking and how it applies to React apps](#100-explain-tree-shaking-and-how-it-applies-to-react-apps) |

</details>

---

<br>

## 🟢 Basic Level

<br>

### 1. What is React?

React (also known as React.js or ReactJS) is an **open-source front-end JavaScript library** developed and maintained by Meta (Facebook). It is used to build fast, component-based user interfaces, especially for single-page applications (SPAs).

React was created by **Jordan Walke**, a software engineer at Facebook. It was first deployed on Facebook's News Feed in **2011** and on Instagram in **2012**, and was open-sourced in **2013**.

**Key reasons developers use React:**
- **Component-based architecture** — build reusable, self-contained UI pieces
- **Virtual DOM** — efficient UI updates without manipulating the real DOM directly
- **Unidirectional data flow** — predictable and easier-to-debug state management
- **Large ecosystem** — React Router, Redux, Next.js, React Native, and more
- **Declarative syntax** — describe what the UI should look like; React handles the how

```jsx
// The simplest React component
function Welcome() {
  return <h1>Hello, World!</h1>;
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 2. What is the history behind React evolution?

The history of React starts with **XHP** — a PHP extension created at Facebook in 2010 that allowed XML document fragments as valid PHP expressions. The goal was to prevent cross-site scripting (XSS) and create reusable HTML elements.

However, XHP had a problem: dynamic web applications required frequent server round-trips and still caused full UI re-renders for small changes. To solve this, **Jordan Walke** created a JavaScript prototype called **FaxJS**, inspired by XHP, which eventually became React.

**Key milestones:**

| Year | Milestone |
| ---- | --------- |
| 2010 | XHP created at Facebook |
| 2011 | React internally deployed on Facebook News Feed |
| 2012 | Deployed on Instagram |
| 2013 | Open-sourced at JSConf US |
| 2015 | React Native released |
| 2016 | React 15 — stable production version |
| 2017 | React 16 (Fiber) — complete rewrite of core |
| 2019 | React 16.8 — Hooks introduced |
| 2022 | React 18 — Concurrent features, automatic batching |
| 2024 | React 19 — Actions API, React Compiler |

> **Note:** JSX syntax was directly inspired by XHP.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 3. What are the major features of React?

| Feature | Description |
| ------- | ----------- |
| **JSX** | Syntax extension that allows writing HTML inside JavaScript |
| **Virtual DOM** | Lightweight copy of real DOM; minimizes direct DOM manipulation |
| **Component-based** | UI is built with reusable, composable components |
| **Unidirectional data flow** | Data flows from parent to child via props |
| **Hooks** | Functions that allow functional components to use state and lifecycle |
| **SSR Support** | Server-side rendering via Next.js for better SEO |
| **React Native** | Build mobile apps using the same React concepts |
| **Concurrent Mode** | (React 18+) Enables interruptible rendering for better UX |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 4. What is JSX in React?

JSX (JavaScript XML) is a **syntax extension for JavaScript** that allows you to write HTML-like code directly inside JavaScript. JSX is **not valid JavaScript** — it is compiled by tools like **Babel** into regular `React.createElement()` calls before the browser executes it.

```jsx
// JSX syntax
const element = <h1 className="title">Hello, Sisi!</h1>;

// What Babel compiles it to behind the scenes
const element = React.createElement("h1", { className: "title" }, "Hello, Sisi!");
```

**Important JSX rules:**
- Use `className` instead of `class`
- Use `htmlFor` instead of `for`
- All tags must be self-closed or have a closing tag: `<img />`, `<br />`
- A component must return a **single root element** (use `<>...</>` Fragment if needed)
- JavaScript expressions go inside `{ }` curly braces

```jsx
function UserCard({ name, role }) {
  return (
    <div className="card">
      <h2>{name}</h2>
      <p>Role: {role.toUpperCase()}</p>
    </div>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 5. What are the differences between Real DOM and Virtual DOM?

| Feature | Real DOM | Virtual DOM |
| ------- | -------- | ----------- |
| Definition | Actual browser DOM | Lightweight JavaScript copy of DOM |
| Updates | Slow — entire tree may re-render | Fast — only changed nodes update |
| Memory usage | Higher | Lower |
| Manipulation | Direct | Indirect — through React reconciliation |
| Re-render trigger | Any change | Only when state/props change |

**How Virtual DOM works:**
1. React maintains a virtual DOM (a plain JS object tree)
2. When state/props change, a new virtual DOM tree is created
3. React **diffs** the old vs new virtual DOM (diffing algorithm)
4. Only the actual changed nodes are updated in the real DOM — this is called **Reconciliation**

```
State/Props Change
       ↓
New Virtual DOM Created
       ↓
Diffing (Old vs New)
       ↓
Minimal Real DOM Update (Reconciliation)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 6. What are components in React?

Components are the **building blocks of a React application**. A component is an independent, reusable piece of UI that returns JSX. Every React app is a tree of components.

There are two types:
- **Functional components** — JavaScript functions (modern, preferred)
- **Class components** — ES6 classes (legacy)

```jsx
// Functional Component
function Button({ label, onClick }) {
  return <button onClick={onClick}>{label}</button>;
}

// Usage
<Button label="Click Me" onClick={() => alert('Clicked!')} />
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 7. What is the difference between functional and class components?

| Feature | Functional Component | Class Component |
| ------- | -------------------- | --------------- |
| Syntax | JavaScript function | ES6 class |
| State | `useState` hook | `this.state` |
| Lifecycle | `useEffect` hook | Lifecycle methods |
| `this` keyword | Not needed | Required |
| Performance | Lighter | Slightly heavier |
| Readability | Simpler | More boilerplate |
| Modern usage |   Recommended |   Legacy |

```jsx
// Functional Component (modern)
function Counter() {
  const [count, setCount] = React.useState(0);
  return <button onClick={() => setCount(count + 1)}>Count: {count}</button>;
}

// Class Component (legacy)
class Counter extends React.Component {
  state = { count: 0 };
  render() {
    return (
      <button onClick={() => this.setState({ count: this.state.count + 1 })}>
        Count: {this.state.count}
      </button>
    );
  }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 8. What are props in React?

Props (short for **properties**) are **read-only inputs** passed from a parent component to a child component. They allow data and functions to flow down the component tree.

```jsx
// Parent passes props
function App() {
  return <UserCard name="Sisi" role="Developer" age={20} />;
}

// Child receives and uses props
function UserCard({ name, role, age }) {
  return (
    <div>
      <h2>{name}</h2>
      <p>{role} — Age: {age}</p>
    </div>
  );
}
```

> **Rule:** Props are **immutable** — a child component cannot modify its own props. They are owned by the parent.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 9. What is state in React?

State is a **built-in JavaScript object** that stores data local to a component. Unlike props, state is **mutable** — when state changes, React re-renders the component and its children.

```jsx
import { useState } from 'react';

function Toggle() {
  const [isOn, setIsOn] = useState(false); // initial state = false

  return (
    <button onClick={() => setIsOn(!isOn)}>
      {isOn ? '  ON' : '  OFF'}
    </button>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 10. What is the difference between state and props?

| Feature | Props | State |
| ------- | ----- | ----- |
| Who manages it? | Parent component | Component itself |
| Mutable? |   No (read-only) |   Yes |
| Triggers re-render? | When parent re-renders | When updated via setter |
| Used for | Passing data down | Managing internal data |
| Accessible to child? |   Yes (passed down) |   No (unless lifted up) |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 11. What is the significance of keys in React lists?

The `key` prop is a **unique identifier** that React uses to track which items in a list have changed, been added, or been removed during reconciliation. Without keys, React re-renders the entire list.

```jsx
const users = [
  { id: 1, name: 'Sisi' },
  { id: 2, name: 'Yamini' },
  { id: 3, name: 'Pavani' }
];

function UserList() {
  return (
    <ul>
      {users.map(user => (
        <li key={user.id}>{user.name}</li>  //   Use unique ID as key
      ))}
    </ul>
  );
}
```

> ⚠️ **Best practice:** Use unique IDs as keys. Avoid using array `index` as key when the list can be reordered or filtered — it causes bugs.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 12. What is conditional rendering in React?

Conditional rendering means dynamically showing or hiding components/elements based on certain conditions. Common approaches:

```jsx
function Dashboard({ isLoggedIn, count }) {
  // 1. Ternary operator
  return (
    <div>
      {isLoggedIn ? <p>Welcome back!</p> : <p>Please log in.</p>}

      {/* 2. Short-circuit && */}
      {isLoggedIn && <button>Logout</button>}

      {/* 3. ⚠️ count can be 0 which renders "0", use > 0 */}
      {count > 0 && <p>You have {count} notifications</p>}
    </div>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 13. How do you render a list in React?

Use `Array.map()` to iterate over an array and return JSX elements. Always provide a unique `key` prop.

```jsx
const skills = ['React', 'Node.js', 'MongoDB', 'TypeScript'];

function SkillList() {
  return (
    <ul>
      {skills.map(skill => (
        <li key={skill}>⚡ {skill}</li>
      ))}
    </ul>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 14. What are React Fragments?

React Fragments let you group multiple child elements **without adding an extra DOM node** like a `<div>`. Useful when returning multiple elements from a component.

```jsx
//   Adds unnecessary <div> to DOM
function Info() {
  return (
    <div>
      <h1>Title</h1>
      <p>Description</p>
    </div>
  );
}

//   No extra node — uses Fragment shorthand <>
function Info() {
  return (
    <>
      <h1>Title</h1>
      <p>Description</p>
    </>
  );
}

// Full syntax (use when you need a key prop)
items.map(item => (
  <React.Fragment key={item.id}>
    <dt>{item.term}</dt>
    <dd>{item.description}</dd>
  </React.Fragment>
));
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 15. What are controlled components?

A controlled component is one where **React state drives the form element's value**. The input's value is always in sync with state.

```jsx
import { useState } from 'react';

function LoginForm() {
  const [email, setEmail] = useState('');
  const [password, setPassword] = useState('');

  const handleSubmit = (e) => {
    e.preventDefault();
    console.log({ email, password });
  };

  return (
    <form onSubmit={handleSubmit}>
      <input
        type="email"
        value={email}
        onChange={e => setEmail(e.target.value)}
      />
      <input
        type="password"
        value={password}
        onChange={e => setPassword(e.target.value)}
      />
      <button type="submit">Login</button>
    </form>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 16. What are uncontrolled components?

Uncontrolled components manage their own form state via the **DOM itself**. You access values using `useRef` instead of state.

```jsx
import { useRef } from 'react';

function SearchBar() {
  const inputRef = useRef(null);

  const handleSearch = () => {
    console.log('Search term:', inputRef.current.value);
  };

  return (
    <>
      <input ref={inputRef} type="text" defaultValue="Initial value" />
      <button onClick={handleSearch}>Search</button>
    </>
  );
}
```

> **When to use:** File inputs (`<input type="file">`) are always uncontrolled. Use uncontrolled when integrating with non-React libraries.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 17. What is the significance of setState in React?

`setState()` is the method in **class components** used to update state. Calling it triggers a re-render of the component and its children.

```jsx
import React, { Component } from 'react';

class Counter extends Component {
  state = { count: 0 };

  increment = () => {
    //   Use callback form when new state depends on previous state
    this.setState(prevState => ({ count: prevState.count + 1 }));
  };

  render() {
    return (
      <div>
        <p>Count: {this.state.count}</p>
        <button onClick={this.increment}>Increment</button>
      </div>
    );
  }
}

export default Counter;
```

> **Note:** `setState` is **asynchronous** — React batches multiple `setState` calls for performance. In functional components, the equivalent is the setter from `useState`.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 18. What are default props?

Default props provide fallback values for props when they are not explicitly passed by the parent.

```jsx
// Method 1: Default parameter values (modern, preferred)
function Button({ label = 'Click Me', color = 'blue', size = 'medium' }) {
  return (
    <button style={{ background: color, fontSize: size === 'large' ? '18px' : '14px' }}>
      {label}
    </button>
  );
}

// Method 2: defaultProps (class components or legacy)
Button.defaultProps = {
  label: 'Click Me',
  color: 'blue'
};
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 19. What is prop drilling?

Prop drilling is the process of passing data through **multiple levels of intermediate components** that don't need the data themselves — they just pass it further down to a deeply nested component.

```
App (has userData)
 └── Layout (passes userData down — doesn't use it)
      └── Sidebar (passes userData down — doesn't use it)
           └── UserAvatar ← actually needs userData
```

**Problems:**
- Hard to maintain — changing prop name requires updating all intermediary components
- Harder to read and understand data flow

**Solutions:**
- React Context API (for moderate complexity)
- State management libraries (Redux, Zustand) for large apps

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 20. What are React events? How are they different from HTML events?

React uses **SyntheticEvents** — a cross-browser wrapper around native DOM events.

| Feature | HTML | React |
| ------- | ---- | ----- |
| Event naming | lowercase (`onclick`) | camelCase (`onClick`) |
| Event handler | String (`"handleClick()"`) | Function reference (`{handleClick}`) |
| Prevent default | `return false` | `e.preventDefault()` |
| Event object | Native | SyntheticEvent (cross-browser) |

```jsx
function Form() {
  const handleSubmit = (e) => {
    e.preventDefault(); // prevents page reload
    console.log('Form submitted');
  };

  const handleKeyDown = (e) => {
    if (e.key === 'Enter') console.log('Enter pressed');
  };

  return (
    <form onSubmit={handleSubmit}>
      <input onKeyDown={handleKeyDown} />
      <button type="submit">Submit</button>
    </form>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 21. What is the children prop?

`children` is a **special built-in prop** in React that represents the content placed between the opening and closing tags of a component. It enables reusable wrapper/container components.

```jsx
function Card({ title, children }) {
  return (
    <div className="card">
      <h2 className="card-title">{title}</h2>
      <div className="card-body">{children}</div>
    </div>
  );
}

// Usage — anything between <Card> tags becomes `children`
function App() {
  return (
    <Card title="About Me">
      <p>I am Sisi, a full-stack developer from Tirupati!</p>
      <button>Follow on Instagram</button>
    </Card>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 22. What is the purpose of React.StrictMode?

`React.StrictMode` is a **development-only tool** that highlights potential problems in your app. It does not render any visible UI or affect production builds.

**What it detects:**
- Components with unsafe lifecycle methods
- Usage of legacy string ref API
- Usage of deprecated `findDOMNode`
- Unexpected side effects (by intentionally double-invoking certain functions)
- Components not handling cleanup properly

```jsx
// index.js
import { createRoot } from 'react-dom/client';
import { StrictMode } from 'react';

const root = createRoot(document.getElementById('root'));
root.render(
  <StrictMode>
    <App />
  </StrictMode>
);
```

> **React 18 Behaviour:** In development, StrictMode intentionally **renders components twice** and **invokes effects twice** to help detect side effects.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 23. What are PropTypes in React?

PropTypes is a **runtime type-checking library** for props. It helps catch bugs during development by validating that the correct type of prop is passed to a component.

```jsx
import PropTypes from 'prop-types';

function UserProfile({ name, age, isActive, role }) {
  return (
    <div>
      <p>{name} — {role}</p>
      <p>Age: {age} | Active: {isActive ? 'Yes' : 'No'}</p>
    </div>
  );
}

UserProfile.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number.isRequired,
  isActive: PropTypes.bool,
  role: PropTypes.oneOf(['admin', 'user', 'editor'])
};
```

> **Modern alternative:** Use **TypeScript** for compile-time type safety — preferred in modern projects.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 24. How do you add inline styles in React?

In React, inline styles are passed as a **JavaScript object** with camelCase property names (not a CSS string).

```jsx
function StyledBox() {
  const boxStyle = {
    backgroundColor: 'tomato',   // not 'background-color'
    padding: '16px',
    borderRadius: '8px',
    color: '#fff',
    fontWeight: 'bold'
  };

  return <div style={boxStyle}>I am a styled box</div>;
}

// Or inline directly (less readable for multiple properties)
<p style={{ fontSize: '18px', color: 'navy' }}>Hello</p>
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 25. What is create-react-app? Is it still relevant?

`create-react-app` (CRA) was the **official React project scaffolding tool** that set up a full React development environment with zero configuration.

**Current status:** CRA is **no longer actively maintained** as of 2023. The React team itself no longer recommends it.

**Modern alternatives:**

| Tool | Best for |
| ---- | -------- |
| **Vite** | Fast dev server, most popular for SPAs today |
| **Next.js** | SSR, SSG, full-stack React apps |
| **Remix** | Full-stack React with nested routing |
| **Astro** | Content-focused websites with React islands |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — React Hooks

<br>

### 26. What are React Hooks? Why were they introduced?

React Hooks are **special built-in functions** introduced in **React 16.8** that allow functional components to use state, lifecycle, and other React features — without writing class components.

**Why were they introduced?**
- Class components had complex, hard-to-understand lifecycle methods
- Stateful logic was difficult to reuse between components (HOCs and render props caused "wrapper hell")
- `this` binding in classes was confusing

**Rules of Hooks:**
1.   Only call hooks at the **top level** — not inside loops, conditions, or nested functions
2.   Only call hooks from **React functional components** or custom hooks

**Built-in hooks:**

| Hook | Purpose |
| ---- | ------- |
| `useState` | Local component state |
| `useEffect` | Side effects |
| `useContext` | Consume Context |
| `useReducer` | Complex state logic |
| `useRef` | DOM access / mutable values |
| `useMemo` | Memoize computed values |
| `useCallback` | Memoize function references |
| `useLayoutEffect` | Sync DOM measurements |
| `useId` | Generate unique IDs |
| `useTransition` | Defer non-urgent updates |
| `useDeferredValue` | Debounce-like value deferral |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 27. Explain useState hook in detail

`useState` is the most fundamental React hook. It adds **local state** to a functional component and returns an array with the current state value and a setter function.

```jsx
const [state, setState] = useState(initialValue);
```

```jsx
import { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  //   May produce stale state when batched
  const badIncrement = () => setCount(count + 1);

  //   Safe — always uses latest state
  const increment = () => setCount(prev => prev + 1);

  // Updating an object state — must spread previous state
  const [user, setUser] = useState({ name: 'Sisi', age: 20 });
  const updateAge = () => setUser(prev => ({ ...prev, age: prev.age + 1 }));

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={increment}>+1</button>
    </div>
  );
}
```

> **Important:** `setState` does NOT merge objects automatically like class component `setState`. You must spread the existing state manually.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 28. Explain useEffect hook and all its dependency cases

`useEffect` lets you perform **side effects** in functional components — like fetching data, setting up subscriptions, or manually manipulating the DOM.

```jsx
import { useState, useEffect } from 'react';

function DataFetcher({ userId }) {
  const [user, setUser] = useState(null);

  // --- CASE 1: No dependency array ---
  // Runs after EVERY render (mount + every update)
  useEffect(() => {
    console.log('Runs on every render');
  });

  // --- CASE 2: Empty array [] ---
  // Runs ONLY ONCE after initial mount (like componentDidMount)
  useEffect(() => {
    console.log('Runs only once on mount');
  }, []);

  // --- CASE 3: With dependencies ---
  // Runs when userId changes
  useEffect(() => {
    fetch(`/api/users/${userId}`)
      .then(res => res.json())
      .then(data => setUser(data));
  }, [userId]);

  // --- CASE 4: With cleanup ---
  // Cleanup function runs on unmount OR before the next effect runs
  useEffect(() => {
    const timer = setInterval(() => console.log('tick'), 1000);
    return () => clearInterval(timer); // ← cleanup
  }, []);

  return <p>{user?.name}</p>;
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 29. Explain useRef hook and its use cases

`useRef` returns a **mutable ref object** whose `.current` property persists for the full lifetime of the component — **without causing re-renders** when changed.

**Use cases:**
1. Access and manipulate DOM elements directly
2. Store mutable values that shouldn't trigger re-render (e.g., previous state, timer IDs)
3. Keep reference to the latest value inside stale closures

```jsx
import { useRef, useState, useEffect } from 'react';

function StopWatch() {
  const [time, setTime] = useState(0);
  const intervalRef = useRef(null); // store timer ID without re-render

  const start = () => {
    intervalRef.current = setInterval(() => setTime(t => t + 1), 1000);
  };

  const stop = () => clearInterval(intervalRef.current);

  return (
    <div>
      <p>Time: {time}s</p>
      <button onClick={start}>Start</button>
      <button onClick={stop}>Stop</button>
    </div>
  );
}

// DOM access example
function AutoFocusInput() {
  const inputRef = useRef(null);

  useEffect(() => {
    inputRef.current.focus(); // focus input on mount
  }, []);

  return <input ref={inputRef} placeholder="Auto focused" />;
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 30. Explain useContext hook

`useContext` lets any component **consume a React Context value** without prop drilling through intermediate components.

```jsx
import { createContext, useContext, useState } from 'react';

// Step 1: Create the context
const ThemeContext = createContext('light');

// Step 2: Provide the context at a high level
function App() {
  const [theme, setTheme] = useState('dark');

  return (
    <ThemeContext.Provider value={{ theme, setTheme }}>
      <Navbar />
      <Page />
    </ThemeContext.Provider>
  );
}

// Step 3: Consume anywhere in the tree — no prop drilling
function Navbar() {
  const { theme, setTheme } = useContext(ThemeContext);

  return (
    <nav style={{ background: theme === 'dark' ? '#333' : '#fff' }}>
      <button onClick={() => setTheme(t => t === 'dark' ? 'light' : 'dark')}>
        Toggle Theme
      </button>
    </nav>
  );
}
```

> **Caveat:** Every component that consumes the context will **re-render** when the context value changes. Split contexts to avoid unnecessary re-renders.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 31. Explain useReducer hook

`useReducer` is an alternative to `useState` for managing **complex state logic**. It follows the Redux pattern — state is updated via dispatching named actions to a reducer function.

```jsx
import { useReducer } from 'react';

const initialState = { count: 0, step: 1 };

function reducer(state, action) {
  switch (action.type) {
    case 'increment':
      return { ...state, count: state.count + state.step };
    case 'decrement':
      return { ...state, count: state.count - state.step };
    case 'reset':
      return initialState;
    case 'setStep':
      return { ...state, step: action.payload };
    default:
      throw new Error(`Unknown action: ${action.type}`);
  }
}

function Counter() {
  const [state, dispatch] = useReducer(reducer, initialState);

  return (
    <div>
      <p>Count: {state.count} | Step: {state.step}</p>
      <button onClick={() => dispatch({ type: 'increment' })}>+</button>
      <button onClick={() => dispatch({ type: 'decrement' })}>-</button>
      <button onClick={() => dispatch({ type: 'setStep', payload: 5 })}>Step: 5</button>
      <button onClick={() => dispatch({ type: 'reset' })}>Reset</button>
    </div>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 32. Explain useMemo hook

`useMemo` **memoizes the result of a computation** and only recomputes it when one of its dependencies changes. Prevents expensive calculations from running on every render.

```jsx
import { useState, useMemo } from 'react';

function ProductList({ products, category }) {
  const [searchTerm, setSearchTerm] = useState('');

  // Without useMemo: filters on EVERY render (even if products/category didn't change)
  // const filtered = products.filter(p => p.category === category);

  // With useMemo: only recomputes when products or category changes
  const filteredProducts = useMemo(() => {
    console.log('Filtering...'); // notice how often this runs
    return products.filter(p => p.category === category);
  }, [products, category]);

  return (
    <div>
      <input value={searchTerm} onChange={e => setSearchTerm(e.target.value)} />
      {filteredProducts.map(p => <p key={p.id}>{p.name}</p>)}
    </div>
  );
}
```

> ⚠️ **Don't over-use useMemo.** Memoization itself has a cost. Only use it when you've profiled and identified a genuine performance bottleneck.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 33. Explain useCallback hook

`useCallback` **memoizes a function reference** so it doesn't get recreated on every render. Useful when passing callbacks to child components wrapped in `React.memo`.

```jsx
import { useState, useCallback } from 'react';

function Parent() {
  const [count, setCount] = useState(0);
  const [otherState, setOtherState] = useState(false);

  // Without useCallback: new function on every Parent render
  // → Child re-renders even when count didn't change
  // const handleClick = () => console.log('Clicked');

  // With useCallback: same function reference until deps change
  const handleClick = useCallback(() => {
    console.log('Clicked');
  }, []); // no deps — created only once

  return (
    <>
      <button onClick={() => setOtherState(s => !s)}>Toggle (triggers Parent re-render)</button>
      <MemoizedChild onClick={handleClick} />
    </>
  );
}

const MemoizedChild = React.memo(function Child({ onClick }) {
  console.log('Child rendered'); // won't fire unless onClick ref changes
  return <button onClick={onClick}>Click</button>;
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 34. What is the difference between useMemo and useCallback?

| Hook | What it memoizes | Returns |
| ---- | ---------------- | ------- |
| `useMemo` | Result of a function call | The computed **value** |
| `useCallback` | The function itself | The memoized **function** |

```jsx
// useMemo — memoizes value
const sortedList = useMemo(() => items.sort(), [items]);

// useCallback — memoizes function
const handleSort = useCallback(() => {
  setSortedItems(items.sort());
}, [items]);

// useMemo and useCallback are equivalent — useCallback(fn, deps) = useMemo(() => fn, deps)
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 35. What are custom hooks? Write an example

Custom hooks are **reusable JavaScript functions** that extract and share stateful logic between components. They must start with `use` and can call other hooks internally.

```jsx
// Custom hook — useFetch
import { useState, useEffect } from 'react';

function useFetch(url) {
  const [data, setData] = useState(null);
  const [loading, setLoading] = useState(true);
  const [error, setError] = useState(null);

  useEffect(() => {
    let isMounted = true;
    setLoading(true);

    fetch(url)
      .then(res => {
        if (!res.ok) throw new Error('Network response was not ok');
        return res.json();
      })
      .then(json => { if (isMounted) { setData(json); setLoading(false); } })
      .catch(err => { if (isMounted) { setError(err.message); setLoading(false); } });

    return () => { isMounted = false; }; // cleanup to prevent state update on unmounted component
  }, [url]);

  return { data, loading, error };
}

// Usage in any component
function UserList() {
  const { data: users, loading, error } = useFetch('https://api.example.com/users');

  if (loading) return <p>Loading...</p>;
  if (error) return <p>Error: {error}</p>;
  return users.map(u => <p key={u.id}>{u.name}</p>);
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 36. What is useLayoutEffect? How is it different from useEffect?

| Hook | When it fires | Blocking? | Use case |
| ---- | ------------- | --------- | -------- |
| `useEffect` | After browser paint (async) | No | API calls, subscriptions |
| `useLayoutEffect` | After DOM mutations, before browser paint (sync) | Yes | DOM measurements, prevent visual flicker |

```jsx
import { useRef, useLayoutEffect } from 'react';

function Tooltip({ children, targetRef }) {
  const tooltipRef = useRef(null);

  // useLayoutEffect: measure DOM before the browser paints
  // prevents flickering when positioning tooltip
  useLayoutEffect(() => {
    const target = targetRef.current.getBoundingClientRect();
    tooltipRef.current.style.top = `${target.bottom + 8}px`;
    tooltipRef.current.style.left = `${target.left}px`;
  }, []);

  return <div ref={tooltipRef} className="tooltip">{children}</div>;
}
```

> **Rule of thumb:** Use `useEffect` for 99% of cases. Use `useLayoutEffect` only when you need to read DOM layout and synchronously re-render before the user sees the result.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 37. What is useId hook (React 18)?

`useId` generates a **stable unique ID** that is consistent between server and client renders. It's used to associate accessible form labels with inputs.

```jsx
import { useId } from 'react';

function FormField({ label, type = 'text' }) {
  const id = useId(); // generates something like ":r1:"

  return (
    <div>
      <label htmlFor={id}>{label}</label>
      <input id={id} type={type} />
    </div>
  );
}

// Each instance generates its own unique ID
<FormField label="Email" type="email" />
<FormField label="Password" type="password" />
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 38. What is useTransition hook?

`useTransition` marks a state update as **non-urgent**, allowing React to prioritize more urgent updates (like user typing) and defer the expensive re-render.

```jsx
import { useState, useTransition } from 'react';

function SearchPage({ allItems }) {
  const [query, setQuery] = useState('');
  const [results, setResults] = useState(allItems);
  const [isPending, startTransition] = useTransition();

  const handleSearch = (e) => {
    const value = e.target.value;
    setQuery(value); // urgent — update input immediately

    startTransition(() => {
      // non-urgent — can be interrupted if user types again
      setResults(allItems.filter(item => item.includes(value)));
    });
  };

  return (
    <div>
      <input value={query} onChange={handleSearch} placeholder="Search..." />
      {isPending && <p>Updating results...</p>}
      <ul>{results.map(r => <li key={r}>{r}</li>)}</ul>
    </div>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 39. What is useDeferredValue hook?

`useDeferredValue` accepts a value and returns a **deferred version** of it — the deferred value lags behind when the UI is busy. It's like a built-in debounce for React rendering.

```jsx
import { useState, useDeferredValue, useMemo } from 'react';

function SearchResults({ allItems }) {
  const [query, setQuery] = useState('');
  const deferredQuery = useDeferredValue(query); // lags behind query during busy renders

  const results = useMemo(() => {
    return allItems.filter(item => item.toLowerCase().includes(deferredQuery.toLowerCase()));
  }, [allItems, deferredQuery]); // only recalculates when deferredQuery settles

  return (
    <div>
      <input value={query} onChange={e => setQuery(e.target.value)} />
      {/* shows stale results while computing, then updates */}
      <ul>{results.map(r => <li key={r}>{r}</li>)}</ul>
    </div>
  );
}
```

| | `useTransition` | `useDeferredValue` |
|-|-----------------|--------------------|
| Controls | State setter | A value |
| Use when | You control the state update | You receive a value from parent/props |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — Component Patterns & Lifecycle

<br>

### 40. What are the lifecycle methods in a class component?

React class components go through three phases with specific methods:

**Mounting (component is created):**
- `constructor()` — Initialize state and bind methods
- `static getDerivedStateFromProps()` — Sync state from props before render
- `render()` — Returns JSX
- `componentDidMount()` — Runs after first render (good for API calls, subscriptions)

**Updating (state or props change):**
- `static getDerivedStateFromProps()`
- `shouldComponentUpdate()` — Return false to prevent re-render
- `render()`
- `getSnapshotBeforeUpdate()` — Capture DOM info before update
- `componentDidUpdate()` — Runs after re-render

**Unmounting:**
- `componentWillUnmount()` — Cleanup subscriptions, timers, event listeners

```jsx
class UserProfile extends React.Component {
  state = { user: null };

  componentDidMount() {
    fetchUser(this.props.userId).then(user => this.setState({ user }));
  }

  componentDidUpdate(prevProps) {
    if (prevProps.userId !== this.props.userId) {
      fetchUser(this.props.userId).then(user => this.setState({ user }));
    }
  }

  componentWillUnmount() {
    // cancel subscriptions, clear timers
  }

  render() {
    return <p>{this.state.user?.name}</p>;
  }
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 41. What is the component lifecycle in functional components?

In functional components, the entire lifecycle is handled via `useEffect`:

```jsx
import { useState, useEffect } from 'react';

function UserProfile({ userId }) {
  const [user, setUser] = useState(null);

  // componentDidMount equivalent
  useEffect(() => {
    fetchUser(userId).then(setUser);
  }, []);

  // componentDidUpdate equivalent
  useEffect(() => {
    fetchUser(userId).then(setUser);
  }, [userId]);

  // componentWillUnmount equivalent (cleanup)
  useEffect(() => {
    const subscription = subscribe(userId);
    return () => subscription.unsubscribe(); // cleanup on unmount
  }, [userId]);

  return <p>{user?.name}</p>;
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 42. What is React.memo?

`React.memo` is a **higher-order component** that wraps a functional component. It performs a **shallow comparison of props** and skips re-rendering the component if its props haven't changed.

```jsx
import { memo, useState } from 'react';

// Without memo: ProductCard re-renders every time Parent re-renders
// With memo: ProductCard only re-renders if `product` prop changes
const ProductCard = memo(function ProductCard({ product }) {
  console.log(`ProductCard rendered: ${product.name}`);
  return (
    <div>
      <h3>{product.name}</h3>
      <p>₹{product.price}</p>
    </div>
  );
});

function ProductList({ products }) {
  const [filter, setFilter] = useState('');

  return (
    <>
      <input value={filter} onChange={e => setFilter(e.target.value)} />
      {products.map(p => <ProductCard key={p.id} product={p} />)}
    </>
  );
}
```

> **Note:** `React.memo` only does shallow comparison. If you pass objects/arrays/functions as props, use `useMemo`/`useCallback` to ensure stable references.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 43. What are Higher-Order Components (HOC)?

A Higher-Order Component is a **function that takes a component and returns a new, enhanced component**. It's a pattern for code reuse and cross-cutting concerns.

```jsx
// HOC that adds authentication check to any component
function withAuth(WrappedComponent) {
  return function AuthenticatedComponent(props) {
    const isAuthenticated = checkAuth(); // your auth logic

    if (!isAuthenticated) {
      return <Redirect to="/login" />;
    }

    return <WrappedComponent {...props} />;
  };
}

// HOC that adds loading state
function withLoader(WrappedComponent) {
  return function WithLoader({ isLoading, ...rest }) {
    if (isLoading) return <div className="spinner">Loading...</div>;
    return <WrappedComponent {...rest} />;
  };
}

// Usage
const ProtectedDashboard = withAuth(Dashboard);
const DashboardWithLoader = withLoader(ProtectedDashboard);
```

> **Modern alternative:** Custom hooks solve most use cases that previously required HOCs, and are much simpler.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 44. What is the Render Props pattern?

Render props is a pattern where a component **accepts a function as a prop** and calls it to determine what to render. It shares stateful logic between components without HOCs.

```jsx
// MouseTracker component shares mouse position via render prop
function MouseTracker({ render }) {
  const [position, setPosition] = useState({ x: 0, y: 0 });

  return (
    <div
      style={{ height: '300px', border: '1px solid' }}
      onMouseMove={e => setPosition({ x: e.clientX, y: e.clientY })}
    >
      {render(position)} {/* call the render prop with the data */}
    </div>
  );
}

// Usage — consumer decides what to render
<MouseTracker
  render={({ x, y }) => <p>Mouse is at: {x}, {y}</p>}
/>

// Using children as a function (common alternative)
<MouseTracker>
  {({ x, y }) => <Crosshair x={x} y={y} />}
</MouseTracker>
```

> **Modern alternative:** Custom hooks (e.g., `useMousePosition()`) are cleaner and more reusable.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 45. What are React Portals?

Portals allow you to render a child component into a **DOM node outside the parent component's hierarchy** — while still keeping it in React's component tree (events still bubble up normally).

**Use cases:** Modals, tooltips, dropdown menus, notifications

```jsx
import { useState } from 'react';
import { createPortal } from 'react-dom';

function Modal({ isOpen, onClose, children }) {
  if (!isOpen) return null;

  // Renders into #modal-root (outside #root)
  return createPortal(
    <div className="modal-overlay" onClick={onClose}>
      <div className="modal-content" onClick={e => e.stopPropagation()}>
        <button className="close-btn" onClick={onClose}>✕</button>
        {children}
      </div>
    </div>,
    document.getElementById('modal-root') // target DOM node
  );
}

// In public/index.html, add: <div id="modal-root"></div>
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 46. What are Error Boundaries?

Error Boundaries are **class components** that catch JavaScript errors anywhere in their child component tree, log those errors, and display a fallback UI instead of crashing the entire application.

```jsx
import React from 'react';

class ErrorBoundary extends React.Component {
  state = { hasError: false, errorMessage: '' };

  // Updates state so the next render shows fallback UI
  static getDerivedStateFromError(error) {
    return { hasError: true, errorMessage: error.message };
  }

  // Log the error to an error reporting service
  componentDidCatch(error, errorInfo) {
    console.error('Error caught:', error);
    console.error('Component stack:', errorInfo.componentStack);
    // logToService(error, errorInfo);
  }

  render() {
    if (this.state.hasError) {
      return (
        <div>
          <h2>Something went wrong.</h2>
          <p>{this.state.errorMessage}</p>
          <button onClick={() => this.setState({ hasError: false })}>Try Again</button>
        </div>
      );
    }
    return this.props.children;
  }
}

// Usage
<ErrorBoundary>
  <MyUnreliableComponent />
</ErrorBoundary>
```

> **Note:** Error boundaries do NOT catch errors in event handlers, async code, SSR, or errors thrown by the boundary itself. Use `react-error-boundary` package for functional component support.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 47. What is the Context API?

The Context API is React's built-in solution for sharing data globally across a component tree **without prop drilling**.

```jsx
import { createContext, useContext, useState } from 'react';

// Create context with a default value
const AuthContext = createContext(null);

// Create a provider component (best practice: wrap in custom component)
export function AuthProvider({ children }) {
  const [user, setUser] = useState(null);

  const login = (userData) => setUser(userData);
  const logout = () => setUser(null);

  return (
    <AuthContext.Provider value={{ user, login, logout }}>
      {children}
    </AuthContext.Provider>
  );
}

// Create a custom hook for consuming the context
export function useAuth() {
  const context = useContext(AuthContext);
  if (!context) throw new Error('useAuth must be used within AuthProvider');
  return context;
}

// Usage anywhere in the tree
function ProfileButton() {
  const { user, logout } = useAuth();
  return user
    ? <button onClick={logout}>Logout {user.name}</button>
    : <button>Login</button>;
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 48. What is lazy loading in React?

Lazy loading defers loading components until they are actually needed, **reducing the initial bundle size** and improving app startup performance.

```jsx
import { lazy, Suspense } from 'react';
import { Routes, Route } from 'react-router-dom';

// Lazy-loaded components — each becomes a separate bundle
const Home = lazy(() => import('./pages/Home'));
const Dashboard = lazy(() => import('./pages/Dashboard'));
const Settings = lazy(() => import('./pages/Settings'));

function App() {
  return (
    <Suspense fallback={<div className="page-loader">Loading...</div>}>
      <Routes>
        <Route path="/" element={<Home />} />
        <Route path="/dashboard" element={<Dashboard />} />
        <Route path="/settings" element={<Settings />} />
      </Routes>
    </Suspense>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 49. What is React Suspense?

`Suspense` is a React component that **displays a fallback UI** while waiting for its children to finish loading — originally for lazy-loaded components, now extended to async data fetching in React 18+.

```jsx
import { Suspense } from 'react';

// With lazy loading
<Suspense fallback={<Spinner />}>
  <LazyComponent />
</Suspense>

// With React Query in Suspense mode (React 18+)
function UserProfile({ userId }) {
  // This "suspends" while data loads — no isLoading check needed
  const { data: user } = useSuspenseQuery({
    queryKey: ['user', userId],
    queryFn: () => fetchUser(userId)
  });

  return <h1>{user.name}</h1>;
}

// In parent
<Suspense fallback={<ProfileSkeleton />}>
  <UserProfile userId={1} />
</Suspense>
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 50. What is code splitting?

Code splitting is a bundler optimization technique that **splits your JavaScript bundle into smaller chunks** that can be loaded on demand — reducing initial load time.

```jsx
// Route-based splitting (most impactful)
const AdminPanel = lazy(() => import('./pages/AdminPanel'));
const Reports = lazy(() => import('./pages/Reports'));

// Component-level splitting (heavy widgets/libraries)
const RichTextEditor = lazy(() => import('./components/RichTextEditor'));
const DataChart = lazy(() => import('./components/DataChart'));

// Conditional splitting based on user role
const UserModule = lazy(() =>
  user.isAdmin
    ? import('./modules/AdminModule')
    : import('./modules/UserModule')
);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 51. What is forwardRef in React?

`forwardRef` allows a parent component to **pass a ref down to a child component** so the parent can directly access a DOM element inside the child.

```jsx
import { forwardRef, useRef } from 'react';

// Child accepts the forwarded ref
const CustomInput = forwardRef(function CustomInput({ label, ...props }, ref) {
  return (
    <div>
      <label>{label}</label>
      <input ref={ref} {...props} />
    </div>
  );
});

// Parent uses ref to access child's input
function Form() {
  const inputRef = useRef(null);

  const focusInput = () => inputRef.current.focus();

  return (
    <>
      <CustomInput ref={inputRef} label="Name" placeholder="Enter name" />
      <button onClick={focusInput}>Focus Input</button>
    </>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 52. What is reconciliation in React?

Reconciliation is React's **algorithm for efficiently updating the DOM** when state or props change. React compares the previous and new virtual DOM trees and applies the minimum number of changes.

**Key rules of the diffing algorithm:**
1. Elements of **different types** → destroy old tree, build new tree from scratch
2. Elements of the **same type** → update only the changed attributes
3. Lists → use `key` props to match elements across renders efficiently

```
Component re-renders
       ↓
New Virtual DOM Tree
       ↓
Diffing (O(n) algorithm with heuristics)
       ↓
Identify minimal set of changes
       ↓
Commit changes to Real DOM
```

> React Fiber (React 16+) made reconciliation **interruptible** — high-priority updates can pause and resume low-priority work.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 53. What is lifting state up?

Lifting state up means moving **shared state to the closest common ancestor** of the components that need it, so they can both read from and update the same state via props/callbacks.

```jsx
//   Before — duplicate/uncoordinated state
function TemperatureInput() {
  const [temp, setTemp] = useState(0); // each has its own state
}

//   After — state lifted to parent
function Calculator() {
  const [celsius, setCelsius] = useState(0); // shared state in parent

  const toFahrenheit = (c) => (c * 9/5) + 32;

  return (
    <div>
      <TemperatureInput
        scale="Celsius"
        value={celsius}
        onChange={setCelsius}
      />
      <TemperatureInput
        scale="Fahrenheit"
        value={toFahrenheit(celsius)}
        onChange={f => setCelsius((f - 32) * 5/9)}
      />
    </div>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🟡 Medium Level — React Router

<br>

### 54. What is React Router and why is it used?

React Router is the standard **client-side routing library** for React. It enables navigation between different views/pages in a Single Page Application (SPA) without full page reloads — by mapping URLs to components.

**Benefits:**
- Declarative route definitions
- Supports nested routing
- Built-in hooks: `useNavigate`, `useParams`, `useLocation`, `useSearchParams`
- SSR support (via `StaticRouter`)
- Code splitting friendly

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 55. What are the core components of React Router v6?

| Component/Hook | Purpose |
| -------------- | ------- |
| `<BrowserRouter>` | Wraps app; uses HTML5 History API |
| `<Routes>` | Container for all `<Route>` definitions |
| `<Route>` | Maps a URL path to a component |
| `<Link>` | Client-side navigation (no page reload) |
| `<NavLink>` | Like `<Link>` but with active styling |
| `<Navigate>` | Redirect programmatically in JSX |
| `<Outlet>` | Renders matched nested route |
| `useNavigate()` | Programmatic navigation in event handlers |
| `useParams()` | Access URL parameters |
| `useLocation()` | Access current location object |
| `useSearchParams()` | Access and update query string |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 56. Explain the difference between BrowserRouter and HashRouter

| Feature | BrowserRouter | HashRouter |
| ------- | ------------- | ---------- |
| URL format | `example.com/about` | `example.com/#/about` |
| Uses | HTML5 History API | URL hash (`#`) |
| SEO |   Better |   Poor |
| Server config needed? |   Yes (catch-all route) |   No |
| Use case | Modern apps with server support | GitHub Pages, static hosting |

```jsx
import { BrowserRouter } from 'react-router-dom'; // for production apps

// If deploying to a static host without server config:
import { HashRouter } from 'react-router-dom';
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 57. How do you define routes in React Router?

```jsx
import { BrowserRouter, Routes, Route } from 'react-router-dom';
import Home from './pages/Home';
import About from './pages/About';
import UserProfile from './pages/UserProfile';
import NotFound from './pages/NotFound';

function App() {
  return (
    <BrowserRouter>
      <Routes>
        <Route path="/" element={<Home />} />
        <Route path="/about" element={<About />} />
        <Route path="/users/:userId" element={<UserProfile />} />
        <Route path="*" element={<NotFound />} /> {/* 404 fallback */}
      </Routes>
    </BrowserRouter>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 58. How do you pass and access URL parameters using React Router?

```jsx
import { Route, Routes } from 'react-router-dom';
import { useParams } from 'react-router-dom';

// Define route with parameter
<Route path="/products/:productId" element={<ProductDetails />} />

// Access parameter in component
function ProductDetails() {
  const { productId } = useParams();

  return (
    <div>
      <h1>Product ID: {productId}</h1>
      {/* fetch product data using productId */}
    </div>
  );
}

// URL: /products/42 → productId = "42"
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 59. What is nested routing in React Router?

Nested routing allows routes to be defined **inside parent routes** — parent renders `<Outlet>` where the nested route component will appear.

```jsx
import { Routes, Route, Outlet, Link } from 'react-router-dom';

function SettingsLayout() {
  return (
    <div>
      <h2>Settings</h2>
      <nav>
        <Link to="profile">Profile</Link>
        <Link to="security">Security</Link>
      </nav>
      <Outlet /> {/* nested route component renders here */}
    </div>
  );
}

function App() {
  return (
    <Routes>
      <Route path="/settings" element={<SettingsLayout />}>
        <Route index element={<ProfileSettings />} />       {/* /settings */}
        <Route path="profile" element={<ProfileSettings />} /> {/* /settings/profile */}
        <Route path="security" element={<SecuritySettings />} /> {/* /settings/security */}
      </Route>
    </Routes>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 60. How do you implement programmatic navigation?

```jsx
import { useNavigate } from 'react-router-dom';

function LoginForm() {
  const navigate = useNavigate();

  const handleLogin = async (credentials) => {
    try {
      await loginUser(credentials);
      navigate('/dashboard');                   // go to dashboard
      // navigate(-1);                          // go back
      // navigate('/login', { replace: true }); // replace current entry in history
      // navigate('/profile', { state: { from: 'login' } }); // pass state
    } catch (err) {
      console.error('Login failed', err);
    }
  };

  return <form onSubmit={handleLogin}>{/* form fields */}</form>;
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 61. How do you handle protected routes in React Router?

```jsx
import { Navigate, useLocation } from 'react-router-dom';
import { useAuth } from './contexts/AuthContext';

// Protected route wrapper
function PrivateRoute({ children }) {
  const { user } = useAuth();
  const location = useLocation();

  if (!user) {
    // Redirect to login, save current location to redirect back after login
    return <Navigate to="/login" state={{ from: location.pathname }} replace />;
  }

  return children;
}

// Usage in routes
<Routes>
  <Route path="/login" element={<Login />} />
  <Route
    path="/dashboard"
    element={
      <PrivateRoute>
        <Dashboard />
      </PrivateRoute>
    }
  />
</Routes>
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 62. How do you handle query parameters in React Router?

```jsx
import { useSearchParams } from 'react-router-dom';

function SearchPage() {
  const [searchParams, setSearchParams] = useSearchParams();

  const query = searchParams.get('q') || '';
  const page = searchParams.get('page') || '1';

  const handleSearch = (newQuery) => {
    setSearchParams({ q: newQuery, page: '1' }); // updates URL: /search?q=react&page=1
  };

  return (
    <div>
      <input
        value={query}
        onChange={e => handleSearch(e.target.value)}
        placeholder="Search..."
      />
      <p>Page: {page}</p>
    </div>
  );
}
// URL: /search?q=react&page=2
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — State Management

<br>

### 63. What is Redux? Explain its core concepts

Redux is a **predictable state container** for JavaScript apps. It provides a single, centralized store for all application state, with strict rules on how state can be updated.

**Core concepts:**

| Concept | Description |
| ------- | ----------- |
| **Store** | Single source of truth — holds entire app state |
| **Action** | Plain JS object describing what happened: `{ type: 'INCREMENT', payload: 1 }` |
| **Reducer** | Pure function: `(state, action) => newState` |
| **Dispatch** | Method to send actions to the store |
| **Selector** | Function to extract specific data from the store |
| **Middleware** | Extends dispatch for async operations (Thunk, Saga) |

```jsx
// actions.js
export const increment = (amount) => ({ type: 'counter/increment', payload: amount });

// reducer.js
const counterReducer = (state = { value: 0 }, action) => {
  switch (action.type) {
    case 'counter/increment': return { value: state.value + action.payload };
    case 'counter/decrement': return { value: state.value - action.payload };
    default: return state;
  }
};

// In component (using react-redux hooks)
import { useSelector, useDispatch } from 'react-redux';
function Counter() {
  const count = useSelector(state => state.counter.value);
  const dispatch = useDispatch();
  return (
    <button onClick={() => dispatch(increment(1))}>Count: {count}</button>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 64. Explain the data flow in a Redux application

Redux enforces **strict unidirectional data flow:**

```
User Action (click, input, etc.)
         ↓
   dispatch(action)
         ↓
   Reducer(state, action) → new state
         ↓
   Store updates
         ↓
   Connected components re-render
         ↓
   UI reflects new state
```

1. User interacts with UI → component **dispatches an action**
2. Action is a plain object: `{ type: 'ADD_ITEM', payload: item }`
3. The **reducer** receives current state + action, returns new state
4. Store notifies all **subscribed components**
5. Components that selected the changed slice **re-render**

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 65. What is Redux Toolkit? Why is it preferred over vanilla Redux?

Redux Toolkit (RTK) is the **official, opinionated toolset** for Redux development. It eliminates the boilerplate of vanilla Redux.

```jsx
import { createSlice, configureStore } from '@reduxjs/toolkit';

// createSlice generates action creators + reducer in one place
const counterSlice = createSlice({
  name: 'counter',
  initialState: { value: 0 },
  reducers: {
    increment: (state, action) => { state.value += action.payload; }, // Immer allows "mutations"
    decrement: (state, action) => { state.value -= action.payload; },
    reset: (state) => { state.value = 0; }
  }
});

export const { increment, decrement, reset } = counterSlice.actions;

const store = configureStore({
  reducer: { counter: counterSlice.reducer }
});
```

| Feature | Vanilla Redux | Redux Toolkit |
| ------- | ------------- | ------------- |
| Boilerplate | High | Minimal |
| Immer (immutability) | Manual spread | Built-in |
| Async (createAsyncThunk) | Manual setup | Built-in |
| DevTools | Manual | Auto-configured |
| RTK Query | No | Built-in data fetching |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 66. How do you handle async operations in Redux?

```jsx
import { createAsyncThunk, createSlice } from '@reduxjs/toolkit';

// createAsyncThunk handles pending/fulfilled/rejected states
export const fetchUsers = createAsyncThunk('users/fetchAll', async () => {
  const response = await fetch('/api/users');
  return response.json();
});

const usersSlice = createSlice({
  name: 'users',
  initialState: { list: [], loading: false, error: null },
  extraReducers: (builder) => {
    builder
      .addCase(fetchUsers.pending, (state) => { state.loading = true; })
      .addCase(fetchUsers.fulfilled, (state, action) => {
        state.loading = false;
        state.list = action.payload;
      })
      .addCase(fetchUsers.rejected, (state, action) => {
        state.loading = false;
        state.error = action.error.message;
      });
  }
});

// In component
function UserList() {
  const dispatch = useDispatch();
  const { list, loading } = useSelector(state => state.users);

  useEffect(() => { dispatch(fetchUsers()); }, []);

  if (loading) return <Spinner />;
  return list.map(u => <p key={u.id}>{u.name}</p>);
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 67. What is Zustand? How does it compare to Redux?

Zustand is a **small, fast, and scalable state management library** with a minimal API. It's a popular Redux alternative for teams who want simplicity.

```jsx
import { create } from 'zustand';

const useCartStore = create((set, get) => ({
  items: [],
  total: 0,
  addItem: (item) => set(state => ({
    items: [...state.items, item],
    total: state.total + item.price
  })),
  removeItem: (id) => set(state => ({
    items: state.items.filter(i => i.id !== id)
  })),
  clearCart: () => set({ items: [], total: 0 })
}));

// Use in any component — no Provider needed!
function CartButton() {
  const { items, addItem } = useCartStore();
  return <button onClick={() => addItem({ id: 1, name: 'Laptop', price: 50000 })}>
    Cart ({items.length})
  </button>;
}
```

| Feature | Zustand | Redux Toolkit |
| ------- | ------- | ------------- |
| Bundle size | ~1KB | ~15KB |
| Boilerplate | Minimal | Moderate |
| Provider needed |   No |   Yes |
| DevTools |   |   Excellent |
| Learning curve | Very easy | Moderate |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 68. What is the difference between client state and server state?

| Type | Description | Examples | Tools |
| ---- | ----------- | -------- | ----- |
| **Client state** | UI-specific, ephemeral data | Modal open/closed, selected tab, form input, dark mode | useState, Zustand, Redux |
| **Server state** | Remote data from APIs, asynchronous, can be stale | Users list, product data, notifications | React Query, SWR, Apollo |

> **Anti-pattern:** Putting server/API data into Redux. React Query manages caching, deduplication, re-fetching, and background sync automatically.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 69. What is React Query (TanStack Query)?

React Query is a **server state management library** that handles fetching, caching, synchronizing, and updating remote data in React — eliminating the need for `useEffect` + manual loading/error state.

```jsx
import { useQuery, useMutation, useQueryClient } from '@tanstack/react-query';

function Posts() {
  const queryClient = useQueryClient();

  // Fetching data
  const { data: posts, isLoading, error } = useQuery({
    queryKey: ['posts'],
    queryFn: () => fetch('/api/posts').then(r => r.json()),
    staleTime: 5 * 60 * 1000, // consider data fresh for 5 minutes
    retry: 2                   // retry failed requests twice
  });

  // Mutating data
  const { mutate: createPost } = useMutation({
    mutationFn: (newPost) => fetch('/api/posts', { method: 'POST', body: JSON.stringify(newPost) }),
    onSuccess: () => queryClient.invalidateQueries({ queryKey: ['posts'] }) // refetch list
  });

  if (isLoading) return <Spinner />;
  if (error) return <p>Error: {error.message}</p>;
  return posts.map(p => <PostCard key={p.id} post={p} />);
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Performance & Architecture

<br>

### 70. What is React Fiber?

React Fiber is the **complete rewrite of React's core reconciliation algorithm**, introduced in React 16. It enables modern React features like Concurrent Mode.

**What Fiber enables:**
- **Incremental rendering** — split rendering work into small units ("fibers"), process over multiple frames
- **Priority scheduling** — high-priority updates (user input, animations) interrupt and defer low-priority work (data fetching)
- **Pausing & resuming** — work can be paused mid-render to handle urgent updates
- **Error boundaries** — finer-grained error catching

**Before Fiber (React 15):** Rendering was synchronous and blocking — once started, it couldn't be interrupted.

**After Fiber (React 16+):** Rendering is asynchronous and interruptible — enables Concurrent features like `useTransition` and `Suspense`.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 71. What is the difference between the Render Phase and Commit Phase?

| Phase | What happens | Can be interrupted? | Side effects allowed? |
| ----- | ------------ | ------------------- | --------------------- |
| **Render Phase** | React calls component functions, computes new virtual DOM tree |   Yes (Concurrent Mode) |   No |
| **Commit Phase** | React applies DOM changes, runs `useLayoutEffect`, then `useEffect` |   No (synchronous) |   Yes |

> **Why this matters:** The render phase can run multiple times for the same update (in Concurrent Mode). This is why side effects in the render phase (like direct API calls) are bugs — they'd run multiple times.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 72. How do you prevent unnecessary re-renders?

| Technique | Tool | When to use |
| --------- | ---- | ----------- |
| Memoize component | `React.memo` | Child component with stable props |
| Memoize computed value | `useMemo` | Expensive calculations in render |
| Stable function reference | `useCallback` | Callbacks passed to memoized children |
| Mutable value without re-render | `useRef` | Storing timer IDs, previous values |
| Move state down | State colocation | State only used by one subtree |
| Split context | Multiple contexts | Context value changes frequently |
| Defer updates | `useTransition` | Non-urgent state updates |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 73. What is state colocation?

State colocation means placing state **as close as possible to the component that uses it**. Moving state down prevents unnecessary re-renders of unrelated components.

```jsx
//   State too high — entire App re-renders when modal toggles
function App() {
  const [isModalOpen, setIsModalOpen] = useState(false); // used only by Modal
  return (
    <>
      <Header />       {/* re-renders unnecessarily */}
      <MainContent />  {/* re-renders unnecessarily */}
      <Modal isOpen={isModalOpen} onClose={() => setIsModalOpen(false)} />
    </>
  );
}

//   State colocated inside Modal — only Modal re-renders
function App() {
  return (
    <>
      <Header />
      <MainContent />
      <Modal />  {/* manages its own isOpen state */}
    </>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 74. How do you optimize a large list (1000+ items) in React?

Rendering 1000+ DOM elements at once is slow. Use **virtualization** — only render elements currently visible in the viewport.

```jsx
import { FixedSizeList } from 'react-window';

const DATA = Array.from({ length: 10000 }, (_, i) => ({ id: i, name: `Item ${i}` }));

const Row = ({ index, style }) => (
  <div style={style} className="list-item">
    {DATA[index].name}
  </div>
);

function VirtualList() {
  return (
    <FixedSizeList
      height={500}        // viewport height
      width="100%"
      itemCount={DATA.length}
      itemSize={50}       // height of each row
    >
      {Row}
    </FixedSizeList>
  );
}
```

**Libraries:**
- `react-window` — lightweight, simple
- `react-virtual` (TanStack) — modern, flexible
- `react-virtuoso` — full-featured (groups, sticky headers, infinite scroll)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 75. What are common React performance anti-patterns?

| Anti-pattern | Problem | Fix |
| ------------ | ------- | --- |
| Creating objects/arrays in render | New reference every render breaks `React.memo` | Move outside component or use `useMemo` |
| `() => fn()` in JSX | New function reference on every render | Use `useCallback` |
| Everything in global state | Unnecessary re-renders across entire app | Keep state local, lift only when needed |
| `index` as key in dynamic lists | Wrong elements update on reorder/filter | Use unique IDs |
| `useEffect` for derived state | Causes extra render cycle | Compute inline during render |
| Not cleaning up effects | Memory leaks (subscriptions, timers) | Always return cleanup from `useEffect` |
| Premature optimization | Added `useMemo`/`useCallback` everywhere without profiling | Profile first, optimize only bottlenecks |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 76. What is the Compound Component pattern?

Compound components share implicit state through context, acting as a **family of components that work together** — similar to how HTML `<select>` and `<option>` work.

```jsx
import { createContext, useContext, useState } from 'react';

const AccordionContext = createContext();

function Accordion({ children, defaultOpen = null }) {
  const [openId, setOpenId] = useState(defaultOpen);
  const toggle = (id) => setOpenId(prev => prev === id ? null : id);

  return (
    <AccordionContext.Provider value={{ openId, toggle }}>
      <div className="accordion">{children}</div>
    </AccordionContext.Provider>
  );
}

Accordion.Item = function Item({ id, title, children }) {
  const { openId, toggle } = useContext(AccordionContext);
  const isOpen = openId === id;

  return (
    <div>
      <button onClick={() => toggle(id)}>{title} {isOpen ? '▲' : '▼'}</button>
      {isOpen && <div className="content">{children}</div>}
    </div>
  );
};

// Clean usage — no prop drilling
<Accordion defaultOpen="faq1">
  <Accordion.Item id="faq1" title="What is React?">
    React is a UI library...
  </Accordion.Item>
  <Accordion.Item id="faq2" title="What are hooks?">
    Hooks are functions that...
  </Accordion.Item>
</Accordion>
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 77. What is SSR in React? How is it different from CSR?

| Feature | CSR (Client-Side Rendering) | SSR (Server-Side Rendering) |
| ------- | -------------------------- | --------------------------- |
| Initial HTML | Empty `<div id="root">` | Full HTML from server |
| First Contentful Paint | Slow (JS must download first) | Fast |
| SEO | Poor (crawlers may miss JS content) |   Excellent |
| Server load | Low | Higher |
| Interactivity | After JS bundle loads | After hydration |
| Framework | Vite, CRA | Next.js, Remix |

**SSG (Static Site Generation):** Pages pre-built at build time — fastest possible, but content can be stale.

**ISR (Incremental Static Regeneration):** Static pages regenerated at set intervals — best of both worlds.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 78. What is Next.js? Why is it used with React?

Next.js is a **React framework** built on top of React that provides production-grade features out of the box.

| Feature | Description |
| ------- | ----------- |
| **File-based routing** | `/pages/about.tsx` → `/about` route (or `/app` folder in App Router) |
| **SSR / SSG / ISR** | Multiple rendering strategies per page |
| **API Routes** | Backend endpoints in the same project (`/pages/api/`) |
| **Image optimization** | `<Image>` component with automatic lazy loading |
| **React Server Components** | App Router supports RSC for zero client JS |
| **Edge Runtime** | Deploy functions at CDN edge nodes |
| **Built-in CSS/Sass** | Global styles, CSS modules, Tailwind support |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 79. What are React Server Components (RSC)?

React Server Components are components that run **exclusively on the server** — they can directly access databases, APIs, and file systems without sending any JavaScript to the client.

| Feature | Server Component | Client Component |
| ------- | --------------- | ---------------- |
| Runs on | Server only | Browser |
| JS sent to browser |   Zero |   Yes |
| useState / useEffect |   Not allowed |   Yes |
| Direct DB/file access |   Yes |   No |
| Interactivity |   No |   Yes |
| Mark with | (default in App Router) | `'use client'` directive |

```jsx
// app/UserList/page.tsx — Server Component (no 'use client')
async function UserListPage() {
  const users = await db.query('SELECT * FROM users'); // direct DB access!
  return (
    <ul>
      {users.map(u => <li key={u.id}>{u.name}</li>)}
    </ul>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 80. What is Concurrent Mode in React 18?

Concurrent Mode is a set of features in React 18 that allows React to **prepare multiple versions of the UI simultaneously** and prioritize work based on urgency.

**Key concurrent features:**

| Feature | Hook/API | Purpose |
| ------- | -------- | ------- |
| Non-blocking renders | `useTransition` | Mark state updates as non-urgent |
| Stale-while-fresh UI | `useDeferredValue` | Show old content while new content loads |
| Suspense for data | `<Suspense>` | Show fallback while async data loads |
| Automatic batching | Built-in | Batch all state updates (even in timeouts/promises) |

Concurrent Mode is **opt-in** via `createRoot()` in React 18 — apps using the legacy `ReactDOM.render()` don't get concurrent features.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 81. What is automatic batching in React 18?

Batching means React **groups multiple state updates** into a single re-render for performance.

```jsx
// React 17 — only batched inside React event handlers
setTimeout(() => {
  setCount(c => c + 1); // triggers re-render
  setFlag(f => !f);     // triggers another re-render
  // Total: 2 re-renders
}, 1000);

// React 18 — automatic batching EVERYWHERE
setTimeout(() => {
  setCount(c => c + 1);
  setFlag(f => !f);
  // Total: 1 re-render  
}, 1000);

// React 18 also batches in Promises, fetch callbacks, native events
fetch('/api/data').then(() => {
  setData(d);     // batched
  setLoading(false); // batched
  // 1 re-render
});

// To opt out of batching (rare):
import { flushSync } from 'react-dom';
flushSync(() => setCount(c => c + 1)); // forces immediate re-render
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — Testing & Security

<br>

### 82. How do you test React components?

**Testing pyramid for React:**

| Layer | Tool | Tests |
| ----- | ---- | ----- |
| Unit | Jest | Utility functions, custom hooks |
| Component | React Testing Library | Component rendering & behaviour |
| Integration | RTL + MSW | Component with mocked API |
| E2E | Playwright / Cypress | Full user flows in a real browser |

```jsx
import { render, screen, fireEvent } from '@testing-library/react';
import Counter from './Counter';

describe('Counter component', () => {
  test('renders with initial count of 0', () => {
    render(<Counter />);
    expect(screen.getByText('Count: 0')).toBeInTheDocument();
  });

  test('increments count on button click', () => {
    render(<Counter />);
    fireEvent.click(screen.getByRole('button', { name: /increment/i }));
    expect(screen.getByText('Count: 1')).toBeInTheDocument();
  });
});
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 83. What is React Testing Library and how is it different from Enzyme?

| Feature | React Testing Library | Enzyme |
| ------- | --------------------- | ------ |
| Philosophy | Test behaviour like a user | Test implementation details |
| DOM access | Queries by role, text, label | Direct component instance access |
| Maintained |   Actively maintained |   Poorly maintained (React 18 issues) |
| Recommended by React team |   Yes |   No |
| Queries | `getByRole`, `getByText`, `getByLabelText` | `.find()`, `.state()`, `.props()` |

> **RTL principle:** "The more your tests resemble the way your software is used, the more confidence they can give you."

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 84. What is the act() utility in testing?

`act()` ensures all **state updates and effects are processed** before you make assertions. It simulates how React works in a browser.

```jsx
import { act } from 'react';
import { render, screen } from '@testing-library/react';

test('loads and displays user', async () => {
  render(<UserProfile userId={1} />);

  // wait for async state updates
  await act(async () => {
    await new Promise(r => setTimeout(r, 0)); // flush promises
  });

  expect(screen.getByText('Sisi')).toBeInTheDocument();
});

// RTL's waitFor/findBy utilities wrap act() automatically
const userName = await screen.findByText('Sisi'); // preferred way
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 85. What are common security concerns in React apps?

| Vulnerability | Risk | Prevention |
| ------------- | ---- | ---------- |
| XSS via `dangerouslySetInnerHTML` | Execute malicious scripts | Sanitize with DOMPurify before rendering |
| Sensitive data in client state | Exposed in Redux DevTools or browser memory | Never store tokens/secrets in Redux or localStorage |
| Insecure API calls | CSRF, unauthorized access | Use HTTPS, CSRF tokens, proper CORS config |
| Dependency vulnerabilities | Known CVEs in npm packages | Run `npm audit` regularly, use Dependabot |
| Clickjacking | Trick users into clicking hidden elements | Set `X-Frame-Options: DENY` header |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 86. What is XSS and how do you prevent it in React?

XSS (Cross-Site Scripting) is an attack where **malicious scripts are injected into a web page** and executed in the user's browser.

React **automatically escapes** string values in JSX — making it safe by default:

```jsx
const userInput = '<script>alert("hacked!")</script>';

//   React escapes this — renders as text, not HTML
<p>{userInput}</p>

//   dangerouslySetInnerHTML bypasses React's protection
<p dangerouslySetInnerHTML={{ __html: userInput }} /> // DANGEROUS

//   Sanitize before using dangerouslySetInnerHTML
import DOMPurify from 'dompurify';
<p dangerouslySetInnerHTML={{ __html: DOMPurify.sanitize(userInput) }} />
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🔴 Advanced Level — React 19 & Future

<br>

### 87. What are the new features in React 19?

React 19 (released 2024) introduces major new features:

| Feature | Description |
| ------- | ----------- |
| **Actions API** | Functions that manage async transitions automatically |
| **`useActionState`** | Manage state from form actions |
| **`useFormStatus`** | Read status of parent form submission |
| **`useOptimistic`** | Show optimistic UI before server confirms |
| **`use()` hook** | Read resources (promises, context) during render |
| **React Compiler** | Auto-memoization — no more manual `useMemo`/`useCallback` |
| **Document Metadata** | `<title>`, `<meta>` natively supported in components |
| **Asset Preloading** | New APIs to preload stylesheets, fonts, scripts |
| **Ref as prop** | No more `forwardRef` needed — pass `ref` directly |

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 88. What is the React Compiler?

The React Compiler (previously "React Forget") is a **build-time tool** that automatically adds memoization to your components — eliminating the need to manually write `useMemo`, `useCallback`, and `React.memo`.

```jsx
// Before React Compiler — you had to manually memoize
function ProductList({ products, onSelect }) {
  const expensiveSort = useMemo(() => products.sort(...), [products]);
  const handleSelect = useCallback(id => onSelect(id), [onSelect]);
  return <MemoizedList items={expensiveSort} onSelect={handleSelect} />;
}

// After React Compiler — write normal code, compiler handles it
function ProductList({ products, onSelect }) {
  const sorted = products.sort(...); // compiler auto-memoizes
  return <List items={sorted} onSelect={id => onSelect(id)} />; // compiler handles
}
```

> The compiler analyzes your code, understands React's rules, and inserts the right memoizations automatically — without changing runtime behaviour.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 89. What is useOptimistic hook?

`useOptimistic` lets you **show a temporary, optimistic UI state** while an async operation (like an API call) is in progress — then automatically reverts if the operation fails.

```jsx
import { useOptimistic, useState } from 'react';

function TodoList({ todos, addTodo }) {
  const [optimisticTodos, addOptimisticTodo] = useOptimistic(
    todos,
    (currentTodos, newTodo) => [...currentTodos, { ...newTodo, pending: true }]
  );

  const handleAdd = async (text) => {
    const newTodo = { id: Date.now(), text };

    addOptimisticTodo(newTodo); // immediately shows in UI (optimistic)

    try {
      await addTodo(newTodo); // actual server call
    } catch {
      // optimistic state automatically reverts on error
    }
  };

  return (
    <ul>
      {optimisticTodos.map(todo => (
        <li key={todo.id} style={{ opacity: todo.pending ? 0.5 : 1 }}>
          {todo.text} {todo.pending && '(Saving...)'}
        </li>
      ))}
    </ul>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 90. What are Server Actions in React 19?

Server Actions are **async functions marked with `'use server'`** that run exclusively on the server but can be called from client components. They are the mechanism for form submissions and mutations in Next.js App Router.

```jsx
// app/actions.ts
'use server'
export async function createUser(formData: FormData) {
  const name = formData.get('name') as string;
  await db.insert(users).values({ name });
  revalidatePath('/users');
}

// app/CreateUserForm.tsx (Client Component)
'use client'
import { createUser } from './actions';

export function CreateUserForm() {
  return (
    <form action={createUser}>
      <input name="name" placeholder="Enter name" />
      <button type="submit">Create</button>
    </form>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

## 🎯 Scenario & Conceptual Questions (MNC Favourites)

<br>

### 91. When would you use useReducer over useState?

Use `useReducer` when:
- **Multiple related state variables** that update together
- **State transitions have names** (easier to understand and debug)
- **Next state depends on previous state** in complex ways
- You want to **extract state logic outside the component** for testing

```jsx
//   useState — messy with multiple related state vars
const [loading, setLoading] = useState(false);
const [data, setData] = useState(null);
const [error, setError] = useState(null);
const [retryCount, setRetryCount] = useState(0);

//   useReducer — all related state in one place
const [state, dispatch] = useReducer(fetchReducer, {
  loading: false, data: null, error: null, retryCount: 0
});
// dispatch({ type: 'FETCH_START' })
// dispatch({ type: 'FETCH_SUCCESS', payload: data })
// dispatch({ type: 'FETCH_ERROR', payload: error })
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 92. When would you use Context API vs Redux?

| Scenario | Use Context API | Use Redux/Zustand |
| -------- | --------------- | ----------------- |
| Theme (dark/light) |   |   Overkill |
| Auth user info |   |   Both work |
| Language/locale |   |   Overkill |
| Shopping cart |   |   |
| Complex UI state with many updates |   |   |
| App needing DevTools + time travel |   |   |
| Shared state across many features |   |   |

> **Context re-renders ALL consumers** when value changes. Redux only re-renders components that subscribe to the changed slice. For frequently changing data, prefer Redux/Zustand.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 93. How would you handle forms in a large React application?

For simple forms → `useState` + controlled components. For large-scale forms → `React Hook Form`.

```jsx
import { useForm } from 'react-hook-form';
import { z } from 'zod';
import { zodResolver } from '@hookform/resolvers/zod';

// Schema validation with Zod
const schema = z.object({
  email: z.string().email('Invalid email'),
  password: z.string().min(8, 'Minimum 8 characters'),
  age: z.number().min(18, 'Must be 18+')
});

function RegistrationForm() {
  const { register, handleSubmit, formState: { errors, isSubmitting } } = useForm({
    resolver: zodResolver(schema)
  });

  const onSubmit = async (data) => {
    await registerUser(data);
  };

  return (
    <form onSubmit={handleSubmit(onSubmit)}>
      <input {...register('email')} />
      {errors.email && <span>{errors.email.message}</span>}

      <input {...register('password')} type="password" />
      {errors.password && <span>{errors.password.message}</span>}

      <button disabled={isSubmitting}>
        {isSubmitting ? 'Registering...' : 'Register'}
      </button>
    </form>
  );
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 94. How do you architect a large-scale React application?

**Recommended: Feature-based folder structure**

```
src/
├── features/              # Feature modules (primary organization unit)
│   ├── auth/
│   │   ├── components/    # Auth-specific components
│   │   ├── hooks/         # Auth-specific hooks (useAuth)
│   │   ├── api/           # Auth API calls
│   │   ├── store/         # Auth state slice
│   │   └── index.ts       # Public API (barrel export)
│   ├── products/
│   ├── orders/
│   └── dashboard/
├── shared/                # Truly reusable across features
│   ├── components/        # Button, Modal, Table, etc.
│   ├── hooks/             # useFetch, useDebounce, useLocalStorage
│   ├── utils/             # formatDate, formatCurrency, etc.
│   └── types/             # Shared TypeScript types
├── lib/                   # Third-party library setup (axios instance, queryClient)
├── routes/                # Route definitions
└── App.tsx
```

**Key principles:**
- Feature-based (not type-based) folder structure
- Each feature exposes a clean public API via `index.ts`
- Shared components know nothing about specific features
- Absolute imports with path aliases (`@/features/auth`)

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 95. How do you implement authentication in a React app?

**Recommended: JWT + HTTP-only cookies**

```jsx
// 1. Auth Context
const AuthContext = createContext(null);

function AuthProvider({ children }) {
  const [user, setUser] = useState(null);
  const [isLoading, setIsLoading] = useState(true);

  useEffect(() => {
    // Check if user is already logged in on mount
    verifyToken().then(setUser).finally(() => setIsLoading(false));
  }, []);

  const login = async (credentials) => {
    const user = await loginApi(credentials); // server sets HTTP-only cookie
    setUser(user);
  };

  const logout = async () => {
    await logoutApi(); // server clears cookie
    setUser(null);
  };

  return (
    <AuthContext.Provider value={{ user, login, logout, isLoading }}>
      {children}
    </AuthContext.Provider>
  );
}

// 2. Protected Route
function PrivateRoute({ children }) {
  const { user, isLoading } = useAuth();
  if (isLoading) return <Spinner />;
  return user ? children : <Navigate to="/login" replace />;
}

// 3. Axios interceptor for token refresh (if using localStorage JWT)
axiosInstance.interceptors.response.use(
  response => response,
  async error => {
    if (error.response.status === 401) {
      await refreshToken();
      return axiosInstance(error.config); // retry original request
    }
    return Promise.reject(error);
  }
);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 96. What happens when you call setState inside useEffect?

It causes a **second render cycle** — the effect runs after the first render, updates state, which triggers another render.

```jsx
//   Infinite loop — no dependency array
useEffect(() => {
  setCount(count + 1); // runs after every render → triggers render → repeat
});

//   Runs once — empty dependency array
useEffect(() => {
  setCount(0); // only runs on mount
}, []);

//   Runs when source data changes
useEffect(() => {
  setDisplayData(processData(rawData)); // derived from rawData
}, [rawData]);

//   Best practice: compute derived values inline (no setState in effect)
const displayData = useMemo(() => processData(rawData), [rawData]);
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 97. Why should you not update state directly in React?

Direct state mutation **bypasses React's reactivity system** — the component won't re-render because React won't know the state changed.

```jsx
const [user, setUser] = useState({ name: 'Sisi', age: 20 });

//   Direct mutation — React won't detect this change, no re-render
user.age = 21;
setUser(user); // same object reference — React sees no change!

//   Correct — create a new object reference
setUser({ ...user, age: 21 });

// For arrays:
const [items, setItems] = useState([1, 2, 3]);

//   Wrong — mutates array
items.push(4);
setItems(items); // same reference

//   Correct — new array
setItems([...items, 4]);
setItems(prev => prev.filter(i => i !== 2)); // remove item
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 98. What is derived state? Why should you avoid storing it in state?

Derived state is a value **computed from existing state or props**. Storing it separately in state causes bugs (sync issues) and unnecessary re-renders.

```jsx
//   Redundant state — derived from items
function Cart({ items }) {
  const [total, setTotal] = useState(0);

  useEffect(() => {
    setTotal(items.reduce((sum, item) => sum + item.price, 0));
  }, [items]); // easy to forget to update this

  return <p>Total: ₹{total}</p>;
}

//   Compute inline — always in sync, zero extra renders
function Cart({ items }) {
  const total = items.reduce((sum, item) => sum + item.price, 0); // derived

  // If expensive, memoize:
  // const total = useMemo(() => items.reduce(...), [items]);

  return <p>Total: ₹{total}</p>;
}
```

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 99. How does React handle accessibility (a11y)?

```jsx
// 1. Semantic HTML — the foundation
<button onClick={handleClick}>Submit</button> //   not <div onClick={...}>

// 2. ARIA attributes
<input
  aria-label="Search products"
  aria-describedby="search-hint"
  role="searchbox"
/>
<p id="search-hint">Type to search by name or category</p>

// 3. Focus management — important for modals
function Modal({ isOpen, onClose }) {
  const closeRef = useRef(null);

  useEffect(() => {
    if (isOpen) closeRef.current?.focus(); // move focus into modal
  }, [isOpen]);

  return isOpen ? (
    <dialog>
      <button ref={closeRef} onClick={onClose} aria-label="Close modal">✕</button>
      {/* content */}
    </dialog>
  ) : null;
}

// 4. Live regions — for dynamic content (notifications)
<div role="status" aria-live="polite">
  {statusMessage} {/* screen readers announce changes */}
</div>

// 5. useId for label associations
function Field({ label }) {
  const id = useId();
  return (
    <>
      <label htmlFor={id}>{label}</label>
      <input id={id} />
    </>
  );
}
```

> Use `eslint-plugin-jsx-a11y` to catch accessibility issues at dev time.

**[⬆ Back to Top](#table-of-contents)**

<br>

---

### 100. Explain tree shaking and how it applies to React apps

Tree shaking is a **dead code elimination technique** performed by bundlers (Webpack, Vite, Rollup) that removes unused exports from your final bundle — reducing its size.

```jsx
//   Imports entire lodash — bundles ALL of lodash (~70KB gzipped)
import _ from 'lodash';
_.debounce(fn, 300);

//   Named import — bundler tree-shakes to include only debounce (~2KB)
import { debounce } from 'lodash-es'; // use lodash-es for ESM tree-shaking

// React is also tree-shakeable with ESM imports
//   Legacy CommonJS — not tree-shakeable
const React = require('react');

//   ESM — tree-shakeable (React 17+ JSX transform doesn't even need React import)
import { useState, useEffect } from 'react';

// Checking bundle size with:
// - vite-bundle-visualizer
// - webpack-bundle-analyzer
// - bundlephobia.com (check package sizes before installing)
```

**[⬆ Back to Top](#table-of-contents)**

<br>
<br>

<div align="center">

## 🎉 You've covered all 100 ReactJS Interview Questions!

**If this repo helped you prepare, please give it a ⭐**

[![Star this repo](https://img.shields.io/github/stars/sisi-tarak/react-interview-questions?style=social)](https://github.com/sisi-tarak/react-interview-questions)

<br>

### 📲 Follow Sisi for more tech interview prep content

[![Instagram](https://img.shields.io/badge/Instagram-%40sisi__tarakk-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sisi_tarakk)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Sisindri%20Singamsetti-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sisitarak)
[![GitHub](https://img.shields.io/badge/GitHub-sisi--tarak-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sisi-tarak)

---

### 🤝 Want to contribute?

Found a mistake, have a better explanation, or want to add more questions?

**[Open a Pull Request](https://github.com/sisi-tarak/react-interview-questions/pulls)** — all contributions are welcome! 🙌


### 📦 More Interview Repos Coming Soon

| Status | Repository |
| ------ | ---------- |
|   Live | [react-interview-questions](https://github.com/sisi-tarak/react-interview-questions) |
|   Live | [nodejs-interview-questions](https://github.com/sisi-tarak/nodejs-interview-questions) |
|   Live | [mern-interview-questions](https://github.com/sisi-tarak/mern-interview-questions.git) |
| 🔜 Coming | dsa-interview-questions |
| 🔜 Coming | java-interview-questions |
| 🔜 Coming | python-interview-questions |

⭐ **Star this repo to get notified when new repos drop!**

---

## Disclaimer

The questions in this repository are compiled from frequently asked interview questions across MNC companies including TCS, Infosys, Wipro, Cognizant, HCL, Capgemini, Accenture, Amazon, Flipkart, and other product companies. We cannot guarantee these exact questions will appear in your interview. The goal is to build conceptual clarity, not memorization.

Good luck with your interview! 😊

*Made with ❤️ by [Sisi](https://instagram.com/sisi_tarakk) | Helping Telugu tech students crack their dream jobs 🚀*

</div>
