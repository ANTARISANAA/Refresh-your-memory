
## **React**

```
React is a free JavaScript library.
React === Fibers Tree.
```

## **Real DOM**

DOM stands for “Document Object Model”. The DOM in simple words represents the UI of your application. Everytime there is a change in the state of your application UI, the DOM gets updated to represent that change.

## **Virtual DOM**

The virtual DOM is only a virtual representation of the DOM. Everytime the state of our application changes, the virtual DOM gets updated instead of the real DOM.

We can see in this picture Virtual DOM and Browser DOM:

![Resume](/Images/v-dom.PNG)

## **How does React use Virtual DOM**

In React, a state has associeted to each component , and evry piece is a component.
React follows the observable pattern and listens for state changes. When the state of a component changes, React updates the virtual DOM tree. Once the virtual DOM has been updated, React then compares the current version of the virtual DOM with the previous version of the virtual DOM. This process is called “diffing”.

## **React render() function**

render() is where the UI gets updated and rendered. render() is the required lifecycle method in React.
