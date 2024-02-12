# React Inline Styling Project

This project is a part of the ALX Software Engineering curriculum, focusing on React inline styling. The goal is to learn and apply various techniques for styling React components inline, rather than using external CSS files.

## Resources

- [Aphrodite](https://github.com/Khan/aphrodite)
- [Inline styling](https://reactjs.org/docs/dom-elements.html#style)
- [Enzyme Render](https://enzymejs.github.io/enzyme/docs/api/ShallowWrapper/render.html)
- [Enzyme Prop](https://enzymejs.github.io/enzyme/docs/api/ReactWrapper/prop.html)
- [CSS Viewport](https://developer.mozilla.org/en-US/docs/Web/CSS/Viewport_concepts)
- [CSS Media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries)
- [CSS Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations)

## Objectives

- The differences between using a CSS file and inline styling
- How to use a CSS-in-JS tool like Aphrodite
- Applying conditions within JS to implement different styles
- Implementing responsive design to adapt UI based on screen size
- Creating small animations within the app

## Requirements

- All files will be interpreted/compiled on Ubuntu 18.04 LTS using Node 12.x.x and npm 6.x.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- A `README.md` file at the root of the project folder is mandatory

## Tasks

### 0. Inline Styling

- **Task**: Modify the `CourseListRow` component to apply inline styling to change row and header row background colors.
- **Repo**: [GitHub Repository](https://github.com/Evans-Gash/alx-react)
- **Directory**: `0x04-React_inline_styling`
- **Files**: `task_0/dashboard/src/CourseList/CourseListRow.js`, `task_0/dashboard/src/CourseList/CourseListRow.test.js`

### 1. Install Aphrodite

- **Task**: Integrate Aphrodite library and replace CSS files with inline styles for various components.
- **Repo**: [GitHub Repository](https://github.com/Evans-Gash/alx-react)
- **Directory**: `0x04-React_inline_styling`
- **Files**: `task_1/dashboard/src/App/App.js`, `task_1/dashboard/src/BodySection/BodySectionWithMarginBottom.js`, `task_1/dashboard/src/CourseList/CourseList.js`, `task_1/dashboard/src/Header/Header.js`, `task_1/dashboard/src/Login/Login.js`, `task_1/dashboard/src/Notifications/Notifications.js`, `task_1/dashboard/src/App/App.test.js`, `task_1/dashboard/src/BodySection/BodySectionWithMarginBottom.test.js`, `task_1/dashboard/src/CourseList/CourseList.test.js`, `task_1/dashboard/src/Header/Header.test.js`, `task_1/dashboard/src/Login/Login.test.js`, `task_1/dashboard/src/Notifications/Notifications.test.js`

### 2. Conditionally Applying Style

- **Task**: Implement conditional styling for NotificationItem and CourseListRow components using Aphrodite.
- **Repo**: [GitHub Repository](https://github.com/Evans-Gash/alx-react)
- **Directory**: `0x04-React_inline_styling`
- **Files**: `task_2/dashboard/src/Notifications/NotificationItem.js`, `task_2/dashboard/src/Notifications/NotificationItem.test.js`, `task_2/dashboard/src/CourseList/CourseListRow.js`, `task_2/dashboard/src/CourseList/CourseListRow.test.js`

### 3. Responsive Design

- **Task**: Implement media queries for responsive design focusing on large screens and screens under 900px width.
- **Repo**: [GitHub Repository](https://github.com/Evans-Gash/alx-react)
- **Directory**: `0x04-React_inline_styling`
- **Files**: `task_3/dashboard/src/Login/Login.js`, `task_3/dashboard/src/Notifications/Notifications.js`, `task_3/dashboard/src/Notifications/NotificationItem.js`

### 4. Animation

- **Task**: Create animations for Notifications menu and apply them when hovered or new notification arrives.
- **Repo**: [GitHub Repository](https://github.com/Evans-Gash/alx-react)
- **Directory**: `0x04-React_inline_styling`
- **Files**: `task_4/dashboard/src/Notifications/Notifications.js`
