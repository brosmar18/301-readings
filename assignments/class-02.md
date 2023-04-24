## Based on the diagram, what happens first, the 'render' or the 'componentDidMount'?
The `render` method is called before the `componentDidMount`. The order of execution is constructor -> render -> componentDidMount.

## What is the very first thing to happen in the lifecycle of React?
The invocation of the `constructor` is the very first thing to happen.

## Put the following things in order that they happen: componentDidMount, rendr, constructor, componentWillUnmount, React Updates.
1. constructor
2. render
3. componentDidMount
4. React Updates
5. componentWillUnmount

## What does componentDidMount do?
This method is called once the component has been rendered to the DOM. Typically, it is sued for fetching data from an API or a backend service, setting up subscriptions, and initializing third-party libraries that required DOM accesss.

## What types of things can you pass in the props?
You can pass any JS data type or value in the props, including: primitive data types, objects and arrays, functions, and React elements or components.

## What is the big difference between props and state?
1. Props:
    - Read-only: Passed down from parent components to child components and cannot be modified by the child component.
    - External data: Present external data that the component receives from its parent.
    - Unidirectional data flow: Flow down the component tree from parent to child components.
2. State:
    - Mutable: Can be changed within the component using the `setState` method  in class components or the `useState` hook in functinal components.
    - Internal data: Represents the interal data of a component, which can change over time.
    - Localized: Within the component, but can be lifted up to a comoon ancestor component to be shared among multiple components.

## When do we re-render our application?
- When the component's state is updating using `setState` or `useState`. When the parent component passes new or updated props to the child component. When the data provided by a React context changes. When the `forceUpdate` method is called on a class component.

## What are some examples of things that we could store in state?
1. User input values.
2. UI State: Open or closed modals, dropdowns, or collapsible sections.
3. Data fetched from APIs: Lists of data, or individual items.
4. Component-specific data: Timer values, animation states, or visibility of elements.
