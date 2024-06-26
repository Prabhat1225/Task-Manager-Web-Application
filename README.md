# Assignment Title: Task Manager Web Application
# Description:
In this assignment, you will develop a Task Manager web application that allows users to create,
view, update, and delete tasks. The application will consist of frontend, backend, database, and
API components. Users should be able to register, log in, and manage their tasks effectively.

# Snapshots
![Screenshot (1400)](https://github.com/Prabhat1225/Task-Manager-Web-Application/assets/107301804/486d66e6-f656-43d6-a0b0-a6adb741d543)
![Screenshot (1401)](https://github.com/Prabhat1225/Task-Manager-Web-Application/assets/107301804/47fa7a90-d876-4432-a85a-d457c24343f1)
![Screenshot (1404)](https://github.com/Prabhat1225/Task-Manager-Web-Application/assets/107301804/dd76aea7-107b-44d1-a564-f3a65245d897)
![Screenshot (1406)](https://github.com/Prabhat1225/Task-Manager-Web-Application/assets/107301804/39364ef3-ed90-4cfe-964e-02eee2be2ef0)


# Features
# User-side features
* Signup
* Login
* Logout
* Add tasks
* View tasks
* Update tasks
* Delete tasks
# Developer-side features
* Toasts for success and error messages
* Form validations in frontend and backend
* Fully Responsive Navbar
* Token based Authentication
* Use of 404 page for wrong urls
* Relevant redirects
* Global user state using Redux
* Custom Loaders
* Use of layout component for pages
* Use of theme colors
* No external CSS files needed (made using Tailwind CSS)
* Usage of Tooltips
* Dynamic document titles
* Redirect to previous page after login
* Use of various React hooks
* Custom hook also used (useFetch)

# Dependencies
Following are the major dependencies of the project:
* axios
* react
* react-dom
* react-redux
* react-router-dom
* react-toastify
* redux
* redux-thunk
* bcrypt
* cors
* dotenv
* express
* jsonwebtoken
mongoose
# Tools and Technologies
* HTML
* CSS
* Javascript
* Tailwind CSS
* Node.js
* Express.js
* React
* Redux
* Mongodb
# Dev-dependencies
Following are the major dev-dependencies of the project:
* nodemon
* concurrently
# Prerequisites
* Node.js must be installed on the system.
* You should have a MongoDB database.
You should have a code editor (preferred: VS Code)
## Installation and Setup
Install all the dependencies
** npm run install-all **
Create a file named ".env" inside the backend folder. Add data from .env.example file and substitute your credentials there.

# Start the application
** npm start **

Go To -- > [http://localhost:3000](http://localhost:3000/)

# Backend API
- POST     /api/auth/signup
- POST     /api/auth/login
- GET      /api/tasks
- GET      /api/tasks/:taskId
- POST     /api/tasks
- PUT      /api/tasks/:taskId
- DELETE   /api/tasks/:taskId
- GET      /api/profile
# Frontend pages
- /                 Home Screen (Public home page for guests and private dashboard (tasks) for logged-in users)
- /signup           Signup page
- /login            Login page
- /tasks/add        Add new task
- /tasks/:taskId    Edit a task
# npm scripts
At root:

* npm run dev: Starts both backend and frontend
* npm run dev-server: Starts only backend
* npm run dev-client: Starts only frontend
* npm run install-all: Installs all dependencies and dev-dependencies required at root, at frontend and at backend.
Inside frontend folder:

* npm start: Starts frontend in development mode
* npm run build: Builds the frontend for production to the build folder
* npm test: Launches the test runner in the interactive watch mode
* npm run eject: This will remove the single build dependency from the frontend.
Inside backend folder:

* npm run dev: Starts backend using nodemon.
* npm start: Starts backend without nodemon.
