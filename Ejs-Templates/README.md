# ToDoList App Challenge

## Instructions:
1. You are tasked with creating a ToDoList application using Express.js and EJS templating engine.
2. Your application should have endpoints for creating, editing, deleting, and viewing ToDo items.
3. Each ToDo item should be associated with its author, and only the author should be able to modify or delete it.
4. Ensure that user authentication is handled via custom headers containing the author's ID.
5. Use CSS to style your EJS templates. You may search for resources on how to integrate CSS with EJS.

## Folder Structure:
- Models
- Controllers
- Views
- Middlewares
- Helpers
- Routes
- `.env`
- `server.js`

## Required Packages:
1. Express.js
2. Nodemon (for automatic server restart)
3. EJS (templating engine)

## Endpoints:
1. `POST /todos`: Create a new ToDo item.
2. `PUT /todos/:id`: Edit an existing ToDo item.
3. `DELETE /todos/:id`: Delete an existing ToDo item.
4. `GET /todos`: View all ToDo items.

## Middleware:
1. Authentication Middleware: Verify if the author ID in the request headers matches the author of the ToDo item being modified or deleted.

## Instructions for Candidates:
1. Set up the folder structure as described above.
2. Install required packages (`express`, `nodemon`, `ejs`) using npm.
3. Create models for ToDo items and any other necessary entities.
4. Implement controllers to handle CRUD operations for ToDo items.
5. Use EJS templates to render views for different endpoints.
6. Integrate CSS styling with EJS templates. You may need to search for resources on how to achieve this.
7. Implement middleware to handle user authentication.
8. Test your application thoroughly to ensure all functionalities work as expected.

## Additional Notes:
- Pay attention to error handling and validation of user input.
- Ensure your code follows best practices and is well-structured.
- Document your code appropriately.
- Consider deploying your application for further testing and demonstration.


