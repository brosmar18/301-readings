## What does `.map()` return?
- The `.map()` method is used in JS to return a new array.
- It applies a given function to each item in the original array, and the result of each function call is stored in the new array.
- In raect, it's commonly used to create an array of JSX elements by applying a function to each item in a data array.

## If I want to loop through an array and display each value in JSX, how do I do that in React?
- You can loop through an array and display each value in JSX using the `.map()` method.
- Inside the render method or the return statement of a function component, call the `.map()` method on the array and pass a function that returns a JSX element for each item.

## Each list item needs a unique ___?
key.

## What is the purpose of a key?
- Help React identify which items have changed, are added, or are removed when udpating the DOM.
- Maintain the association between components and their DOM elements, ensuring a stable and efficient rendering process.
- When rendering a list of items, it's important to assign a unique key to each item in the list.
- Keys should ideally be stable and unique identifiers, but using the item index as a key is an acceptable fallback when no unique identifier is available.
- **Note**: Using the index as a key can cause performance issues or incorrect behavior in some cases, such as when the list is reordered, so it's better to use unique identifiers when possible.

## What is the spread operators?

- The spread operator is a JavaScript feature, represented by three dots (...).
- It allows you to expand iterable elements (e.g., arrays, strings, or objects) into individual elements or properties.

## List 4 things that the spread operator can do:
1. Combine arrays: Merge multiple arrays into a single array.
2. Clone arrays or objects: Create a shallow copy of an array or an object.
3. Insert new items in an array: Add new elements at any position within an array.
4. Merge objects: Combine the properties of multiple objects into a single object.

## Give an example of using the spread operator to combine two arrays:

```javascript
let array1 = [1, 2, 3];
let array2 = [4, 5, 6];
let combinedArray = [...array1, ...array2]; // [1, 2, 3, 4, 5, 6]
```

## Give an example of using the spread operator to add a new item to an array:
```javascript
let originalArray = [1, 2, 3];
let newItem = 4;
let newArray = [...originalArray, newItem]; //[1, 2, 3, 4]
```
## Give an example of using the spread operator to combine two objects into one:
```javascript
let object1 = {a: 1, b: 2};
let object2 = {c: 3, d: 4};
let combinedObject = {...object1, ...object2}; // { a: 1, b: 2, c: 3, d: 4 }
```

## What is the first thing a developer does to pass functions between components?
The first step is to define the function in the parent component that will be passed to the child component.

## In your own words, what does the increment function do?
It Updates the state of the parent component by incrementing a specific value. It can be used, for example, to increase a counter or change the value of an item in an array.

## How can you pass a method from a parent component into a child component?
You use props. In the parent component, pass the function as a prop to the child component. In the child component, access the function through the `props` object and use it as needed.

## How does the child component invoke a method that was passed to it from a parent component?
The child component can invoke a method passed from a parent component by calling the function received through props, typically as a callback for an event handler.
