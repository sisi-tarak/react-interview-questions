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

| No.| Questions                                                                                                                                                                                                                        |
| ---| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|    | **Core React**                                                                                                                                                                                                                   |
| 1  | [What is React?](#what-is-react)                                                                                                                                                                                                 |
| 2  | [What is the history behind React evolution?](#What-is-the-history-behind-react-evolution)                                                                                                                                       |
| 3  | [What are the major features of React?](#what-are-the-major-features-of-react)                                                                                                                                                   |
| 4  | [What is JSX?](#what-is-jsx)                                                                                                                                                                                                     |
| 5  | [What is the difference between Element and Component?](#what-is-the-difference-between-element-and-component)                                                                                                                   |
| 6  | [How to create components in React?](#how-to-create-components-in-react)                                                                                                                                                         |
| 7  | [When to use a Class Component over a Function Component?](#when-to-use-a-class-component-over-a-function-component)                                                                                                             |
| 8  | [What are Pure Components?](#what-are-pure-components)                                                                                                                                                                           |
| 9  | [What is state in React?](#what-is-state-in-react)                                                                                                                                                                               |
| 10 | [What are props in React?](#what-are-props-in-react)                                                                                                                                                                             |
| 11 | [What is the difference between state and props?](#what-is-the-difference-between-state-and-props)                                                                                                                               |
| 12 | [What is the difference between HTML and React event handling?](#what-is-the-difference-between-html-and-react-event-handling)                                                                                                   |
| 13 | [What are synthetic events in React?](#what-are-synthetic-events-in-react)                                                                                                                                                       |
| 14 | [What are inline conditional expressions?](#what-are-inline-conditional-expressions)                                                                                                                                             |
| 15 | [What is "key" prop and what is the benefit of using it in arrays of elements?](#what-is-key-prop-and-what-is-the-benefit-of-using-it-in-arrays-of-elements)                                                                     |
| 16 | [What is Virtual DOM?](#what-is-virtual-dom)                                                                                                                                                                                     |
| 17 | [How Virtual DOM works?](#how-virtual-dom-works)                                                                                                                                                                                 |
| 18 | [What is the difference between Shadow DOM and Virtual DOM?](#what-is-the-difference-between-shadow-dom-and-virtual-dom)                                                                                                         |
| 19 | [What is React Fiber?](#what-is-react-fiber)                                                                                                                                                                                     |
| 20 | [What is the main goal of React Fiber?](#what-is-the-main-goal-of-react-fiber)                                                                                                                                                   |
| 21 | [What are controlled components?](#what-are-controlled-components)                                                                                                                                                               |
| 22 | [What are uncontrolled components?](#what-are-uncontrolled-components)                                                                                                                                                           |
| 23 | [What is the difference between createElement and cloneElement?](#what-is-the-difference-between-createelement-and-cloneelement)                                                                                                 |
| 24 | [What is Lifting State Up in React?](#what-is-lifting-state-up-in-react)                                                                                                                                                         |
| 25 | [What are Higher-Order components?](#what-are-higher-order-components)                                                                                                                                                           |
| 26 | [What is children prop?](#what-is-children-prop)                                                                                                                                                                                 |
| 27 | [How to write comments in React?](#how-to-write-comments-in-react)                                                                                                                                                               |
| 28 | [What is reconciliation?](#what-is-reconciliation)                                                                                                                                                                               |
| 29 | [Does the lazy function support named exports?](#does-the-lazy-function-support-named-exports)                                                                                                                                   |
| 30 | [Why React uses className over class attribute?](#why-react-uses-classname-over-class-attribute)                                                                                                                                 |
| 31 | [What are fragments?](#what-are-fragments)                                                                                                                                                                                       |
| 32 | [Why fragments are better than container divs?](#why-fragments-are-better-than-container-divs)                                                                                                                                   |
| 33 | [What are portals in React?](#what-are-portals-in-react)                                                                                                                                                                         |
| 34 | [What are stateless components?](#what-are-stateless-components)                                                                                                                                                                 |
| 35 | [What are stateful components?](#what-are-stateful-components)                                                                                                                                                                   |
| 36 | [How to apply validation on props in React?](#how-to-apply-validation-on-props-in-react)                                                                                                                                         |
| 37 | [What are the advantages of React?](#what-are-the-advantages-of-react)                                                                                                                                                           |
| 38 | [What are the limitations of React?](#what-are-the-limitations-of-react)                                                                                                                                                         |
| 39 | [What are the recommended ways for static type checking?](#what-are-the-recommended-ways-for-static-type-checking)                                                                                                               |
| 40 | [What is the use of react-dom package?](#what-is-the-use-of-react-dom-package)                                                                                                                                                   |
| 41 | [What is ReactDOMServer?](#what-is-reactdomserver)                                                                                                                                                                               |
| 42 | [How to use InnerHtml in React?](#how-to-use-innerhtml-in-react)                                                                                                                                                                 |
| 43 | [How to use styles in React?](#how-to-use-styles-in-react)                                                                                                                                                                       |
| 44 | [How events are different in React?](#how-events-are-different-in-react)                                                                                                                                                         |
| 45 | [What is the impact of indexes as keys?](#what-is-the-impact-of-indexes-as-keys)                                                                                                                                                 |
| 46 | [How do you conditionally render components?](#how-do-you-conditionally-render-components)                                                                                                                                       |
| 47 | [Why we need to be careful when spreading props on DOM elements??](#why-we-need-to-be-careful-when-spreading-props-on-dom-elements)                                                                                              |
| 48 | [How do you memoize a component?](#how-do-you-memoize-a-component)                                                                                                                                                               |
| 49 | [How you implement Server-Side Rendering or SSR?](#how-you-implement-server-side-rendering-or-ssr)                                                                                                                               |
| 50 | [How to enable production mode in React?](#how-to-enable-production-mode-in-react)                                                                                                                                               |
                                                                                                                                
</details>


---

## Core React

1.  ### What is React?

   

    **[⬆ Back to Top](#table-of-contents)**


---

## Disclaimer

The questions provided in this repository are the summary of frequently asked questions across numerous companies. We cannot guarantee that these questions will actually be asked during your interview process, nor should you focus on memorizing all of them. The primary purpose is for you to get a sense of what some companies might ask — do not get discouraged if you don't know the answer to all of them ⁠— that is ok!

Good luck with your interview 😊

---

