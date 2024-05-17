# PERN TODO 

Perntodo is a simple web application for managing todos, built using the PERN (PostgreSQL, Express.js, React.js, Node.js) stack. This application allows users to create, read, update, and delete todo items.

![Screenshot 2024-05-17 144124](https://github.com/Sumit262601/pern_todo/assets/127303989/02b273f8-0052-489a-8091-07766b90cb0d)

## Technologies Used


- **PostgreSQL**: Database management system used for storing todo data.
- **Express.js**: Backend web application framework for Node.js used for handling HTTP requests.
- **React.js**: Frontend JavaScript library used for building user interfaces.
- **Node.js**: JavaScript runtime environment used for server-side scripting.

## Installation

1. Clone this repository: git clone https://github.com/your-username/perntodo.git

2. Navigate to the project directory: cd `perntodo`

3. Install dependencies:
	- Backend: cd backend && `npm install`
	- Frontend: cd frontend && `npm install`
4. Set up PostgreSQL database:
	- Create a PostgreSQL database named `perntodo`.
	- Import the database schema from `backend/database/schema.sql`.

5. Configure environment variables:
   	- Create db.js in your project's server folder then follow the steps below.
	```
 	user: "your database_user name",
 	password: "your database_password",
 	host: "localhost",
 	port: "your database_port",
 	database: "your database_name",
	```
	- Start the backend server: `cd backend && npm start`
	- Start the frontend development server: `cd frontend && npm start`
	- Open your browser and navigate to `http://localhost:5000` to access the Perntodo application.

7. Usage
   - Upon accessing the application, you'll receive a list of existing todo items.
   - You can create a new todo item by clicking the "Add Todo" button and completing the form.
   - To edit or delete an existing todo item, click the respective buttons next to the todo item.
   - Todos can also be marked as completed by checking the checkbox next to each item.
