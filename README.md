This is a simple To-Do List project built using Python Flask and SQLAlchemy for database management. The application allows users to add, update, and delete tasks with a title and description. The project is under development. 

Please note- the descriptions are not visible here but i will fix it soon.


Features:

Add Task: Users can add new tasks with a title and description.

Update Task: Existing tasks can be updated with new information.

Delete Task: Users can delete tasks from the to-do list.

View Tasks: The application displays all tasks on the main page.



Technologies Used:

Python: The main programming language used for the backend logic.
Flask: A lightweight web framework for building web applications in Python.
SQLAlchemy: A SQL toolkit and Object-Relational Mapping (ORM) library for Python, used for database management.
SQLite: A lightweight, file-based database engine used to store tasks.
Bootstrap: Front-end framework for styling and layout.


Project Structure:

app.py: Contains the main Flask application code.

templates/: Directory for HTML templates used by Flask.

Todo.db: SQLite database file storing task information.


Here's a brief overview of the files in the "templates" folder:

1. base.html
Purpose:
The base.html file serves as the base template for other HTML files in the project.
It includes the common structure, navigation bar, and Bootstrap styling shared across multiple pages.
Other HTML files, such as index.html and update.html, extend this base template to maintain a consistent layout.

2. index.html
Purpose:
The index.html file represents the main page of the To-Do List application.
It extends the base.html template and includes sections for adding new tasks and displaying the list of existing tasks.
Users can input task details in a form, submit the form, and view their tasks in a table.

3. update.html
Purpose:
The update.html file provides a page for updating existing tasks in the To-Do List.
It extends the base.html template and includes a form pre-filled with the details of the selected task.
Users can modify the task title and description and submit the form to update the task.



Contributing
If you would like to contribute to the project, feel free to fork the repository and submit pull requests. Bug reports and feature requests are welcome!
