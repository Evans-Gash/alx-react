# 0x07. React Redux action creator+normalizr

## Front-end
- JavaScript
- ES6
- React


## Resources
Read or watch:
- [Normalizr](https://github.com/paularmstrong/normalizr)
- [Normalizing State Shape](https://redux.js.org/recipes/structuring-reducers/normalizing-state-shape/)
- [Redux Getting started and core concepts](https://redux.js.org/introduction/getting-started)
- [Redux Actions](https://redux.js.org/basics/actions)
- [Async Actions](https://redux.js.org/advanced/async-actions)
- [Writing tests for Redux](https://redux.js.org/recipes/writing-tests)

## Learning Objectives
- Normalizr’s purpose and how to use it
- Schemas and normalization of nested JSON
- Core concepts of Redux
- Redux actions
- Redux action creators
- Async actions in Redux
- How to write tests for Redux

## Requirements
- Allowed editors: vi, vim, emacs, Visual Studio Code
- files should end with a new line
- files will be interpreted/compiled on Ubuntu 18.04 LTS using node 12.x.x and npm 6.x.x
- A README.md file is mandatory
- Push all of your files, including package.json and .babelrc
- All of your functions must be exported

## Tasks
### 0. Read data from a JSON
- Reuse the latest dashboard project from React course 0x06-React_state
- Place notifications.json into the root of the project directory and use the data inside for the next step
- Create a new notifications.js file in a schema folder and implement the required function
- Create tests for the function

### 1. Normalize a nested JSON
- Copy the dashboard from the previous task into a task_1 directory at the root of the project
- Modify src/schema/notifications.js to set up a schema using Normalizr
- Create tests to verify normalized data

### 2. Filter a normalized Schema
- Copy the contents of dashboard from task_1 directory into task_2 directory
- Modify the function getAllNotificationsByUser to use the normalized dataset

### 3. Create actions for the course list
- Copy the dashboard folder from the task_2 directory into a directory named task_3
- Create action types and creators for course list interactions
- Write tests for the action creators

### 4. Create actions for the UI
- Copy the dashboard folder from task_3 into a directory labeled task_4
- Create action types and creators for UI interactions
- Write tests for the action creators

### 5. Create actions for the notification list
- Copy dashboard from the task_4 directory into task_5
- Create action types and creators for notification list interactions
- Write tests for the action creators

### 6. Bound the actions
- Modify the Course, Notification, and UI action creators to bind actions

### 7. Async Action Creators
- Set up Redux and Redux Thunk
- Simulate an API
- Create Async Action Creators
- Write tests for Async Action Creators
