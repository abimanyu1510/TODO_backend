# Todo-app Rest API

This is a simple Todo app REST API built with [NodeJS, ExpressJS].
Database - Mongo DB

## Feature of Todo App
- Create, Read, Update, Delete (CRUD) operations for Todos
- Authentication and Authorization
- Filtering and Sorting
- Error Handling

<ul>
<li><b>API Structure:</b> The backend of this to-do app is crafted with Express.js, allowing smooth communication between the front end and the server through a well-organized RESTful API.<li>

<li><b>Database Integration:</b> We use MongoDB to store user details and tasks. This ensures that your data is saved safely and can be easily accessed whenever you need it.</li>

<li> <b>User Authentication:</b> To keep your information secure, we've implemented JWT (JSON Web Tokens). This means you can register, log in, and stay connected without worries about your session being compromised.</li>

<li><b>Task Management:</b> Our API makes it easy to handle your tasks with simple CRUD (Create, Read, Update, Delete) operations. You can create new tasks, view what you have, update their status, or delete them whenever you want.</li>

<li><b>Middleware Magic:</b> We’ve added some custom middleware for error handling and request authentication. This helps ensure that only authorized users can access specific parts of the app.</li>

<li><b>Environment Variables:</b> Sensitive information like database connection strings and JWT secrets is stored in environment variables. This keeps your data safe and allows for easy changes when needed.</li>

<li><b>Testing and Validation:</b> To keep everything running smoothly, we’ve included input validation. This ensures that the data you send is safe and secure, along with tests to confirm that all API endpoints are functioning as they should.</li>
</ul>

