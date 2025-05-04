# Mission Frontend

A curated list of JavaScript, React, machine coding problems, pattern questions, basic backend knowledge, and fundamental questions all in one place.

---

## HTML and CSS3

* **DOM and Attributes**

  * Difference between `innerText` and `textContent`
  * What is the use of `data` attribute
  * Difference between `loading="lazy"` and `loading="eager"` on `<img>` tag
  * Semantic vs Non-semantic elements
* **CSS Units and Layout**

  * Difference between `rem`, `em`, and `px`
  * Making cards responsive vertically (without using media queries)
  * Difference between `max-width` and `min-width`
  * Why use `border: transparent` over `border: none`
* **HTML Basics**

  * How to check which HTML version is used
  * Difference between HTML4 and HTML5
  * When to use Tailwind, CSS, SCSS — and their differences
  * What are pseudo-classes
  * Difference between inline and block elements
* **Problem Statements**

  * Add a background image and text above it. Add opacity to background image without affecting the text.
  * Difference between `display: none` and `visibility: hidden`
  * Flex vs Grid layout — when to use which
  * Media Queries

---

## JavaScript

* **Script Loading**

  * Difference between `async` and `defer`

* **Concepts & Patterns**

  * Interface and whether methods can be added in Interface
  * SOLID Principles
  * `call`, `apply`, and `bind`
  * Abstraction in JS — private variables/methods
  * Callback hell and Promise chaining — how to avoid both
  * Falsy values in JS
  * Difference between `undefined` and `null`
  * Difference between `==` and `===`
  * Exception handling
  * Difference between `i++` and `++i`
  * What happens when an API is fetched — DNS involvement

* **Functions & Execution**

  * Event bubbling — explanation + example
  * Difference between `forEach` and `map`
  * Type conversion — output-based questions
  * Event loop — Microtask vs Macrotask queue
  * Constructors in JS
  * Comparing two objects
  * Currying and infinite currying
  * `this` keyword in arrow functions
  * Reassignment/redeclaration in `const` with arrays/objects
  * IIFE

* **Problem Statements**

  * Polyfill for `Array.map()` and `Promise.all()`
  * Write a function to create an object from string (e.g. input: "x.y.z", value: "convert") → output: `{x: {y: {z: "convert"}}}`
  * Difference between `preventDefault` and `stopPropagation`
  * Debouncing with edge case where another function should be aborted if needed
  * Write a JS function that takes an object and a callback, executes callback after 3 seconds
  * Create function that takes (function, interval, frequency), calls function `frequency` times with `interval` delay, with cancel control

* **Polyfills**

  * `this`, `call`, `bind`, `apply` and their polyfills

* **Output Based**

  * `console.log(undefined || 5 && 9 || 2);`

---

## Machine Coding Questions (Vanilla JS / React)

* **Timers & Counters**

  * Toggle Start/Stop button with a counter that resumes after stop
  * Stopwatch (HH\:MM\:SS) with Start, Stop, and Reset

* **API Integration**

  * Fetch todos and group by user blocks
  * Two mock APIs → merge student data by unique registration ID
  * Products API → List with checkbox, delete button, mark as completed with line-through
  * Products API → Pagination with 10 items per page, loading state, forward/prev arrows
  * Products API → Sidebar filters by discount %, clear filters, show message if none

* **Forms & Inputs**

  * Multi-step form with Next/Previous buttons and persistence
  * Form validation with rules (name, age, email, password)
  * Reusable Input component with validation by type (text/number/email)

* **Structures & UI**

  * Stack UI: push, pop, top, isEmpty
  * Previous/Next functionality with counter
  * Input box + array display, find second largest number
  * React quadrants (Microsoft logo style) — clicked state toggle
  * Radio buttons to mix colors
  * Checkbox list with master checkbox and indeterminate state
  * Toast message (disappears after 5s)
  * Reusable card component styled via `type` prop
  * Input-to-ASCII converter (+10 char code)

* **Optimization**

  * Large list rendering optimizations

---

## DSA

* Sum of digits at even places
* Recursive factorial
* Rotational strings
* Multiply recursively (without `*` operator)
* Max occurring string in an array
* Convert array to linked list
* Flatten array (no JS inbuilt methods)
* Recursive char print + vowel check
* Matching braces array + sort pairs
* Group array into sub-arrays of repeating pairs
* Find common interests between users from object
* Sort array without inbuilt methods
* Binary search
* Find 3rd largest element
* Sort array of 0s, 1s, 2s
* Parentheses validator
* Count character occurrences in string
* Remove duplicates from array
* String palindrome check
* Reverse a string
* Capitalize first letter of each word
* Array methods: `filter`, `map`, `reduce`, `slice`, `splice`, `sort`
* Number palindrome check
* Stack and operations
* Convert object to array of key-value arrays
* Higher-order function: `multiply([1,2,3])(2) => [2,4,6]`

---

## React

* **Core Concepts**

  * Dependency Injection
  * Higher-Order Components (HOCs)
  * Design Patterns
  * SOLID Principles in React
  * Virtual DOM
  * Lazy Loading & Suspense
  * Protected Routes
  * Lifting State Up
  * Controlled vs Uncontrolled Components
  * Class-based vs Functional Components

* **Optimization & Performance**

  * Memoization: `useMemo`, `useCallback`
  * CSR vs SSR
  * Asset optimization

* **State Management**

  * Redux vs Context
  * Multiple stores/contexts
  * Batching
  * Prop drilling and solutions

* **Component Design**

  * Folder architecture
  * Reusable components
  * Children props
  * `useReducer` vs `useState`
  * `useCallback` returns what?

* **Hooks & Lifecycle**

  * `useEffect` vs `useLayoutEffect`
  * Cleanup function in `useEffect`
  * Lifecycle methods
  * Can you use `this` in functional components?
  * `useEffect` dependency array — what goes inside?

* **JSX & Babel**

  * Render h2 with className without JSX
  * What is Babel?
  * Why is React fast?

* **Framework Comparison**

  * React vs Vue vs Angular
  * What problems does Next.js solve over React
  * Declarative vs Imperative

* **Advanced**

  * Why setState is async
  * Pure components
  * Parent-child re-render logic
  * Create `useAsync` custom hook (returns loading, error, response)
  * `Switch` in `react-router-dom`
