This project is a simple task manager RESTful API built using Node.js and Express.js. It allows users to perform CRUD operations (Create, Read, Update, Delete) on tasks, where each task has a title, description, and completion status.
Setup

Endpoints

    GET /tasks: Retrieve all tasks.
    GET /tasks/:id: Retrieve a single task by its ID.
    POST /tasks: Create a new task.
    PUT /tasks/:id: Update an existing task by its ID.
    DELETE /tasks/:id: Delete a task by its ID.

Task Schema

{
  "id": 1,
  "title": "Create a new project",
  "description": "Create a new project using Magic",
  "completed": false
}
