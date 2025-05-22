<!-- # React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project. -->


Todo Summary Assistant
A full-stack web application that enables users to manage their tasks efficiently. Users can add, edit, delete, and mark tasks as completed. The application provides a summary of tasks, enhancing productivity and organization.

Tech Stack
Frontend: HTML, CSS, JavaScript

Backend: Node.js, Express.js

Database: MongoDB

Deployment: Netlify (Frontend), Render (Backend)

 Live Demo
Access the deployed application here: https://cool-faun-e349ad.netlify.app/

Features
Add Tasks: Users can add new tasks with a title and description.

Edit Tasks: Modify existing tasks to update details.

Delete Tasks: Remove tasks that are no longer needed.

Mark as Completed: Toggle tasks between completed and pending states.

Task Summary: View a summary of total, completed, and pending tasks.

Installation & Setup
Clone the repository:

bash
Copy
Edit
git clone https://github.com/bhargavi374/todo.git
cd todo
Install backend dependencies:

bash
Copy
Edit
cd server
npm install
Configure environment variables:

Create a .env file in the server directory and add your MongoDB connection string:

ini
Copy
Edit
MONGODB_URI=your_mongodb_connection_string
Start the backend server:

bash
Copy
Edit
npm start
Open the frontend:

Open client/index.html in your browser or serve it using a live server extension.