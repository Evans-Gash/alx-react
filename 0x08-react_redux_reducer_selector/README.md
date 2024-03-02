# 0x08. React Redux Reducer + Selector

## Overview
This project aims to implement React Redux reducers and selectors for managing state in a React application. It covers the basics of Redux, including writing reducers, handling actions, and using selectors efficiently. The project is managed by Johann Kerbrat, Engineering Manager at Uber Works.

## Learning Objectives
- The purpose of a reducer and its role in an application
- Why reducers should remain as pure functions
- The importance of avoiding mutations within reducers
- Usage of Immutable within reducers
- Integration of Normalizr within the application
- What selectors are and when to use them

## Resources
- [Reducers](https://redux.js.org/basics/reducers)
- [Selectors](https://redux.js.org/recipes/computing-derived-data)
- [Writing tests](https://redux.js.org/recipes/writing-tests)
- [Immutable Map documentation](https://immutable-js.github.io/immutable-js/docs/#/Map)
- [Normalizr](https://github.com/paularmstrong/normalizr)
- [Normalizing State Shape](https://redux.js.org/recipes/structuring-reducers/normalizing-state-shape)

## Requirements
- **Edited by:** Visual Studio Code
- All files end with a new line.
- Interpreted/compiled on Ubuntu 18.04 LTS using Node.js 12.x.x and npm 6.x.x.
- A README.md file at the root of the project folder.
- Push all files, including package.json and .babelrc.
- Export all functions.

## Tasks
### 0. Write a Basic Reducer
- Reuse the latest dashboard project from the React course 0x08-React_Redux_action_creator+normalizr.
- Create the basic state in reducers/uiReducer.js.
- Implement the reducer function according to provided specifications.
- Write tests to verify the functionality of the reducer.

### 1. Use Immutable for the UI Reducer
- Install Immutable.js within the project.
- Update uiReducer.js to use Immutable.js Map.
- Modify the reducer function to utilize Immutable.js set method.
- Update the test suite accordingly.

### 2. Create a Reducer for Courses
- Create load action and define course reducer with default state.
- Implement actions for fetching courses, selecting and unselecting courses.
- Write tests to validate the functionality of the course reducer.

### 3. Create the Reducer for Notifications
- Define actions for loading notifications, marking as read, and setting type filter.
- Implement reducer function for notifications.
- Write tests to ensure the correctness of the notification reducer.

### 4. Normalizr & Immutable
- Implement Normalizr schema for courses and notifications.
- Update course and notification reducers to use Immutable.js Map and handle normalized data.
- Modify tests to accommodate changes made in reducers.

### 5. Selectors
- Create selectors for notifications reducer to efficiently access data.
- Write tests to validate the functionality of the selectors.

## Repository Information
- **GitHub Repository:** [alx-react](https://github.com/Evans-Gash/alx-react)
- **Directory:** 0x08-react_redux_reducer_selector
- **Files:**
  - task_0/dashboard/src/reducers/uiReducer.js, task_0/dashboard/src/reducers/uiReducer.test.js
  - task_1/dashboard/src/reducers/uiReducer.js, task_1/dashboard/src/reducers/uiReducer.test.js
  - task_2/dashboard/src/actions/courseActionTypes.js, task_2/dashboard/src/reducers/courseReducer.js, task_2/dashboard/src/reducers/courseReducer.test.js
  - task_3/dashboard/src/actions/notificationActionTypes.js, task_3/dashboard/src/reducers/notificationReducer.js, task_3/dashboard/src/reducers/notificationReducer.test.js
  - task_4/dashboard/src/schema/courses.js, task_4/dashboard/src/reducers/courseReducer.js, task_4/dashboard/src/schema/notifications.js, task_4/dashboard/src/reducers/notificationReducer.js, task_4/dashboard/src/reducers/courseReducer.test.js, task_4/dashboard/src/reducers/notificationReducer.test.js
  - task_5/dashboard/src/selectors/notificationSelector.js, task_5/dashboard/src/selectors/notificationSelector.test.js
