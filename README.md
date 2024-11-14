# Todo App

A simple and intuitive Todo application built with React and Vite. This app lets users add, update, delete, and toggle the status of todos. The UI is designed with Tailwind CSS, giving it a clean and responsive look.

## Features

- **Add Todo:** Easily add new tasks to your list.
- **Update Todo:** Modify the text of existing todos.
- **Delete Todo:** Remove completed or irrelevant tasks.
- **Toggle Todo:** Mark tasks as completed or uncompleted.

## Tech Stack

- **React.js:** Core library for building the UI, utilizing `useState`, `useEffect`, and `Context API` for state management and reactivity.
- **Vite:** Fast and lightweight development environment with HMR (Hot Module Replacement) for rapid development.
- **Tailwind CSS:** Utility-first CSS framework for styling.
## Starting with React + Vite

This project is built using Vite, which provides a minimal setup to get React running with HMR and ESLint rules.

### Plugins Used

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) - Uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) - Uses [SWC](https://swc.rs/) for Fast Refresh

## Screenshots

### Add Todo
![Add Todo](./screenshots/add_todo.png)

This screenshot shows the "Add Todo" feature, where users can input a new task and add it to the list.

### Update Todo
![Update Todo](./screenshots/update_todo.png)

Here, the "Update Todo" feature allows users to modify the text of an existing task.

### Delete Todo
![Delete Todo](./screenshots/delete_todo.png)

The "Delete Todo" feature enables users to remove tasks they no longer need.

### Toggle Todo
![Toggle Todo](./screenshots/toggle_todo.png)

With the "Toggle Todo" feature, users can mark tasks as completed or not, helping them keep track of their progress.

## Code Overview

### `useState`

Manages the state of todos, including new additions, updates, and deletions.

### `useEffect`

Syncs todos with local storage or external APIs when needed.

### Context API

Provides global state management, making the state accessible throughout the component tree without prop drilling.

## License

This project is licensed under the MIT Lisence.
