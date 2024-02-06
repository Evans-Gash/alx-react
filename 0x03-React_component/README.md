# React Component Project README

## Overview
This project focuses on building and testing React components, including the utilization of class components, lifecycle methods, event handling, Higher Order Components (HOCs), and optimizing performance. The project aims to enhance your understanding of React components and their usage in building scalable and efficient front-end applications.

## Resources
To successfully complete this project, it's recommended to read or watch the following resources:
- [React components](https://reactjs.org/docs/components-and-props.html)
- [React Developer Tools](https://reactjs.org/blog/2019/08/15/new-react-devtools.html)
- [Enzyme Shallow](https://enzymejs.github.io/enzyme/docs/api/shallow.html)
- [Enzyme Mount](https://enzymejs.github.io/enzyme/docs/api/mount.html)
- [Enzyme Unmount](https://enzymejs.github.io/enzyme/docs/api/unmount.html)
- [React Pure components](https://reactjs.org/docs/react-api.html#reactpurecomponent)
- [React Higher Order Components](https://reactjs.org/docs/higher-order-components.html)
- [Jest mock function](https://jestjs.io/docs/mock-functions)

## Learning Objectives
By the end of this project, you should be able to explain to anyone, without the help of Google:
- When to use a Class or a function to create a component
- The lifecycle of a Class component
- How to test a component
- How to utilize a Jest spy to verify that a function is being called correctly
- What an HOC is and how to use it
- How to optimize performance and control which components to render

## Requirements
- All files will be interpreted/compiled on Ubuntu 18.04 LTS using Node 12.x.x and npm 6.x.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- A `README.md` file at the root of the project folder is mandatory

## Tasks
### 0. Commence with class components
Start this project with files from the last task of the 0x03. React Props project. Convert the App function into a React Class. Ensure the tests are still passing.

### 1. Lifecycles
Add lifecycle methods to a component. Implement an event listener to trigger actions on key press combinations. Write tests to verify the functionality.

### 2. Handling Events
Create a new event handling function within a component and pass it as a property to a child component. Test the functionality of the event handling.

### 3. Reusable comments & specialization
Implement containment and specialization within components. Create new components with specific functionalities.

### 4. Specialization
Create a new component with specific styling and functionalities based on another component.

### 5. Use the new components
Integrate newly created components into the main App component to enhance its functionality and visual appeal.

### 6. Test the new components
Write tests to ensure the newly created components render correctly and perform as expected.

### 7. Create WithLogging HOC
Implement a Higher Order Component (HOC) to log component mount and unmount events. Modify the HOC to display component names for debugging purposes.

### 8. Write a test for the HOC
Write unit tests to validate the functionality of the Higher Order Component (HOC) created in the previous task.

### 9. Declare a pure component
Modify a component to make it a "pure" component, ensuring it only updates when necessary.

### 10. Make your own pure component
Implement a custom pure component that optimizes rendering based on specific conditions.

### 11. Add a test
Write tests to verify the rendering behavior of the pure component under different scenarios.

## Repository Information
- **GitHub Repository:** alx-react
- **Directory:** 0x03-React_component
