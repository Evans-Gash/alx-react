# 0x09. React Redux Connectors and Providers

## Overview
This project focuses on integrating Redux with a React application, specifically exploring Redux connectors and providers. By implementing Redux architecture, developers will gain insights into state management, actions, reducers, and middleware. Furthermore, this project introduces Redux Thunk for handling asynchronous actions and Redux DevTools for debugging.

## Learning Objectives
- Redux connectors and their usage
- Functions passed to a connector: mapStateToProps, mapDispatchToProps
- Mapping action creators to components using connectors
- Implementing async action creators with Redux Thunk
- Setting up Redux Providers for app store
- Enhancing connector performance using Reselect
- Debugging application state using Redux DevTools

## Resources
Refer to the following resources for guidance:

- [Redux CreateStore](https://redux.js.org/api/createstore)
- [Redux Connect](https://react-redux.js.org/api/connect)
- [Redux Provider](https://react-redux.js.org/api/provider)
- [Redux Middleware](https://redux.js.org/tutorials/fundamentals/part-4-store#middleware)
- [Redux Thunk](https://github.com/reduxjs/redux-thunk)
- [Redux DevTools](https://github.com/zalmoxisus/redux-devtools-extension)
- [Redux Reselect](https://github.com/reduxjs/reselect)

## Requirements
- Editors:Visual Studio Code
- All files must end with a new line
- Mandatory README.md file at the project root
- Project files should be interpreted/compiled on Ubuntu 18.04 LTS using node 12.x.x and npm 6.x.x
- Push all project files, including package.json and .babelrc
- Export all functions

## Tasks
1. **Write mapStateToProps** - Implement mapStateToProps function to connect uiReducer to the component's isLoggedIn property.
   - File: `task_0/dashboard/src/App/App.js`

2. **Create a Small Store** - Set up a store containing the uiReducer state and implement a provider for the main App.
   - File: `task_0/dashboard/src/index.js`

3. **Test MapStateToProps** - Write tests to ensure mapStateToProps function returns the correct object.
   - File: `task_0/dashboard/src/App/App.test.js`

4. **Connect Action Creators** - Connect displayNotificationDrawer and hideNotificationDrawer action creators to the component.
   - File: `task_1/dashboard/src/App/App.js`

5. **Refactor Code** - Refactor code by removing old functions and state properties related to drawer display.
   - File: `task_1/dashboard/src/App/App.js`

6. **Update Tests** - Update test suites to reflect code changes and ensure all tests pass.
   - Files: `task_1/dashboard/src/App/App.test.js`, `task_1/dashboard/src/Footer/Footer.test.js`, `task_1/dashboard/src/Header/Header.test.js`, `task_1/dashboard/src/reducers/uiReducer.test.js`

7. **Async Actions & Thunk Middleware** - Implement LoginRequest and logout action creators using Redux Thunk middleware.
   - File: `task_2/dashboard/src/index.js`

8. **Connect LoginRequest to the App** - Connect the loginRequest action creator to the component and refactor the component to use the new login function from props.
   - File: `task_2/dashboard/src/App/App.js`

9. **Connect User State to the Footer** - Map the user prop to the user within the Redux state in the Footer component.
   - File: `task_2/dashboard/src/Footer/Footer.js`

10. **Connect Logout Action Creator to the Header** - Connect the Header component to the logout action creator and modify the render function accordingly.
    - File: `task_2/dashboard/src/Header/Header.js`

11. **Modify the uiReducer** - Update the uiReducer to handle LOGIN and LOGOUT actions by setting the user state accordingly.
    - File: `task_2/dashboard/src/reducers/uiReducer.js`

12. **Modify the Test Suites** - Update test suites of different components to support changes in reducers and ensure all tests pass.
    - Files: `task_2/dashboard/src/App/App.test.js`, `task_2/dashboard/src/Footer/Footer.test.js`, `task_2/dashboard/src/Header/Header.test.js`, `task_2/dashboard/src/reducers/uiReducer.test.js`

13. **Understand Redux DevTools Extension** - Install and configure Redux DevTools extension for debugging purposes.
    - File: `task_3/dashboard/src/index.js`

14. **Combine Store: Root Reducer** - Combine reducers into the root reducer.
    - File: `task_4/dashboard/src/reducers/rootReducer.js`

15. **Combine Store: Modify the Application** - Update the application to use the root reducer instead of individual reducers.
    - File: `task_4/dashboard/src/index.js`

16. **Combine Store: Write the Tests** - Modify test suites to support the root reducer and ensure all tests pass.
    - Files: `task_4/dashboard/src/App/App.test.js`, `task_4/dashboard/src/reducers/rootReducer.test.js`

17. **Connect Notifications: New Action Creator** - Implement new action creators for notifications, including setLoadingState, setNotifications, and fetchNotifications.
    - File: `task_5/dashboard/src/actions/notificationActionCreators.js`

18. **Connect Notifications: Improve Reducer** - Enhance the notificationReducer to handle loading state and merge notifications data correctly.
    - File: `task_5/dashboard/src/reducers/notificationReducer.js`

19. **Connect Notifications to the Reducer** - Map listNotifications prop and fetchNotifications action creator to the Notifications component.
    - File: `task_5/dashboard/src/Notifications/Notifications.js`

20. **Connect Notifications: Clean Up** - Remove old functions and test data related to notifications.
    - File: `task_5/dashboard/src/App/App.js`

21. **Connect Notifications: Update the Test Suites** - Update test suites for modified components and ensure all tests pass correctly.
    - Files: `task_5/dashboard/src/reducers/notificationReducer.test.js`, `task_5/dashboard/src/App/App.test.js`, `task_5/dashboard/src/Notifications/Notifications.js`, `task_5/dashboard/src/Notifications/Notifications.test.js`, `task_5/dashboard/src/actions/notificationActionCreators.test.js`

22. **Selectors** - Implement selectors to improve connector performance, specifically for notifications.
    - File: `task_6/dashboard/src/selectors/notificationSelector.js`

23. **Connect Courses: Create a Course Selector** - Create a selector to fetch course entities from the reducer.
    - Files: `task_7/dashboard/src/selectors/courseSelector.js`, `task_7/dashboard/src/selectors/courseSelector.test.js`

24. **Connect Courses: Create a Fetch Courses Function** - Implement fetchCourses function to query the API for course data.
    - Files: `task_7/dashboard/src/actions/courseActionCreators.js`, `task_7/dashboard/src/actions/courseActionCreators.test.js`

25. **Connect the Courses Component** - Connect CourseList component to state and action creators, and fetch course data on mount.
    - Files: `task_7/dashboard/src/CourseList/CourseList.js`, `task_7/dashboard/src/CourseList/CourseList.test.js`

26. **Memoized Selectors: Redux Reselect** - Implement memoized selectors using Redux Reselect for improved performance.
    - File: `task_8/dashboard/src/selectors/notificationSelector.js`

27. **Memoized Selectors: Update the UI** - Update Notifications component to utilize the new selector and filter notifications.
    - File: `task_8/dashboard/src/Notifications/Notifications.js`

28. **Memoized Selectors: Update the Test Suite** - Update test suites for Notifications component and selectors to reflect changes.
    - Files: `task_8/dashboard/src/Notifications/Notifications.test.js`, `task_8/dashboard/src/selectors/notificationSelector.test.js`

29. **Container/Component** - Introduce container/component architecture to simplify component logic and improve testability.
    - Files: `task_9/dashboard/src/Notifications/Notifications.js`, `task_9/dashboard/src/Notifications/Notifications.test.js`, `task_9/dashboard/src/Notifications/NotificationsContainer.js`, `task_9/dashboard/src/Notifications/NotificationsContainer.test.js`

To access the project, follow these steps:

1. Clone the repository:
```bash
git clone git@github.com:Evans-Gash/alx-react.git
```

2. Navigate to the project directory:
```bash
cd alx-react/0x09-react_redux_connectors_and_providers
```
