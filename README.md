# Task Manager

Task Manager is a web application built with React that allows users to manage their tasks efficiently. Users can add new tasks, mark tasks as completed, edit existing tasks, and view all tasks or only completed tasks.

## Features

- Add new tasks with a title and description
- Mark tasks as completed
- Edit existing tasks
- View all tasks or only completed tasks
- Tasks are saved locally and persist across sessions

## Technologies Used

React: The application is built using React, a popular JavaScript library for building user interfaces. React's component-based architecture helps in creating reusable and modular UI components, making the code more maintainable and easier to understand.

Material-UI: Material-UI is used for styling the components. It provides a set of pre-built React components that follow Google's Material Design principles, giving the application a modern and visually appealing look.

LocalStorage: The application uses the browser's localStorage to store the list of tasks and completed tasks. This allows the user's tasks to persist even after refreshing the page or closing the browser.

UUID: The uuid package is used to generate unique IDs for each task. This ensures that each task has a unique identifier, which is useful for updating and deleting tasks.

Icons: Icons from the react-icons package, such as AiOutlineDelete, AiOutlineEdit, and BsCheck, are used to provide visual cues for actions like deleting, editing, and completing tasks.

Context API: Create a context to manage the application's state and provide it to the components that need access to the state. Use the useContext hook to access the context in child components.

Glassmorphism Effect: Apply the glassmorphism effect to the components by using CSS. You can create a CSS class for the effect and apply it to the desired elements.


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
