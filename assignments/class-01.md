## What is a component?
A component is a self-contained, reusable building block for UI in a React application.
It is a JS function or class that returns a React element (JSX).
Components can present UI elements like buttons, forms, or entire sections of a webpage.

## Characteristics of a component:
**Reusability**: Components can be reused in different parts of the application or even across multiple applications.
**Encapsulation**: Components encapsulate4 their own logic, state, and styles. This separation of concerns makes it easier to maintain and test.
**Composition**: Components can be composed together to create complex UIs. Parent components can pass data and functions to child components via props.
**State and Lifecycle**: Components can have their own internal state, which can change over time. Components have lifecycle methods that allow you to run code at specific points in their lifecycle.

## Advantages of using component-based archicecture:

**Modularity**: Breaks down the UI into smaller, more manageable pieces. Simpplifies development and maintenance.
**Reusability**: Reduces code duplication by allowing components to be reused. Encouranges creating reusable components that can be shared across the application or even between different projects.
**Easier Collaboration**: Developers can work on separate components without impacting each other's work. Enables parallel development and reduces merge conflics.
**Cleaner Code**: Smaller, well-defined components make it easier to understand the code. Promotes clean and organized code structure.
**Easier Testing and Debugging**: Isolated components can be tested and debugged independently. Encourages writing testable code and improves overall code quality.

## What is `props` short for?
Props is short for properties. They are used to pass data and functions from parent components to child components in a React application.

## How are props used in React?
1. Padding Data:
    - Parent components pass data to child components as attributes in JSX.
    - This data can be any JS value such as strings, numbers, objects, arrays, or functions.
2. Passing Functions:
    - Functions can be passed as props to child components, enabling communication between components.
    - This allows child components to invoke parent components' functions to update their state or trigger other actions.
3. Defaut Props:
    - Components can define defaut prop values that are used when no value is provided by the parent component.
    This helps maintain consistent behavior and simplifies the component's usage.

## What is the flow of props?
Props flow in a "unidirectional" data blow from parent components to child components. This one-way data flow helps maintain a predictable flow of data and simplifies the application's state mangement. To communicate changes from child components back to parent components, functions are passed as props and called by the child component, updating the parent component's state.
