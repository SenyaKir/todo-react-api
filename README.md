# Todo React API

A simple and interactive Todo application built with React and TypeScript, connected to a REST API.
It allows users to create, update, delete, and filter todos by their completion status.


## Live Preview

[View Live Demo](https://senyakir.github.io/todo-react-api/)


## Technologies Used

**Core**
* **React** (v18.3.1) – UI framework
* **TypeScript** (v5.2.2) – Static type checking
* **SCSS** (v1.77.8) – CSS preprocessor for styling

**State Management**
* **React Hooks** – Application state management (e.g., `useState`, `useEffect` for API synchronization)

**UI/UX**
* **React Router DOM** (v6.25.1) – Application routing and URL-based navigation
* **Bulma** (v1.0.1) – CSS framework for responsive layouts
* **React Transition Group** (v4.4.5) – Smooth UI animations and transitions
* **Classnames** (v2.5.1) – Conditional CSS class management
* **FontAwesome** (v6.5.2) – Iconography

**Development & Deployment**
* **Vite** (v5.3.1) – Fast frontend build tool and development server
* **Cypress** (v13.13.0) – End-to-end (E2E) testing framework
* **ESLint & Prettier** – Code quality and formatting
* **GH-Pages** (v6.1.1) – Hosting and deployment to GitHub Pages


## Getting Started

**Clone the Repository**
  ```bash
    git clone https://github.com/your-username/project-name.git
    cd project-name
  ```

**Install Dependencies**
  ```bash
    npm install
    # or
    yarn install
  ```

**Run the Project Locally**
  ```bash
    npm start
    # or
    yarn start
  ```


## Features

* **Full CRUD**: Create, Read, Update (title/status), and Delete todos via an external API.
* **Smart Filtering**: Switch between All, Active, and Completed tasks.
* **Optimistic Updates/UI Feedback**: Includes loading states (loaders) for individual items during API calls.
* **Batch Operations**: Clear all completed tasks or toggle the status of all tasks at once.
* **Input Validation**: Prevents adding empty tasks and handles API errors gracefully.
* **In-place Editing**: Double-click a todo title to edit it, with Escape to cancel and Enter to save.
