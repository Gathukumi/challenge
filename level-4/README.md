# What are hooks
Hooks are a feature in React, a JavaScript library for building user interfaces, that allow functional components to manage state and side effects, previously associated with class components. They provide a way to reuse stateful logic and lifecycle behaviors within functional components. Hooks include `useState` for managing component state, `useEffect` for handling side effects, and several other built-in and custom hooks for various purposes. They make functional components more powerful and flexible by enabling them to manage component state and interact with React's lifecycle and features.
# Define UseState and UseEffect 
In summary:

1. `useState`: `useState` is a hook in React used to manage and update component state in functional components. It returns a state variable and a function to update that state variable. It allows functional components to maintain and change their state over time.

2. `useEffect`: `useEffect` is a hook in React that enables functional components to perform side effects, such as data fetching, DOM manipulation, or subscriptions. It runs after rendering and can be used to manage side effects in response to changes in the component's state or props.
# What UseState returns when called
 The `useState` hook in React returns an array with two elements: the current state value and a function to update that state. It is used to manage and update component state in functional components.
# Fours basis and four advanced hooks and their use
**Basic Hooks:**

1. `useState`: Manages and updates component state. Use it to store and update simple component-specific data.

2. `useEffect`: Handles side effects, such as data fetching and DOM manipulation. It runs after rendering and is useful for managing asynchronous operations.

3. `useContext`: Provides access to shared data and context within a component tree. It's useful for passing data to deeply nested components without explicit prop drilling.

4. `useRef`: Creates mutable references to DOM elements and other values that persist across renders. It is often used for accessing and managing DOM elements or creating instance variables.

**Advanced Hooks:**

1. `useReducer`: Manages complex state logic using a reducer function, similar to how Redux works. It's suitable for components with intricate state management requirements.

2. `useMemo`: Memoizes and caches expensive computations. Use it to optimize performance by preventing unnecessary recalculations.

3. `useCallback`: Memoizes functions to prevent unnecessary re-renders in child components. It's helpful when you want to optimize performance by ensuring that functions are not recreated on each render.

4. `useLayoutEffect`: Similar to `useEffect`, but it runs synchronously after all DOM mutations. Use it when you need to perform synchronous layout calculations or interact with the DOM immediately after rendering.
