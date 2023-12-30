                    Project Name -  Task Management Project (Using Django Rest Framwork)

Description :-

The Task Management Project is a web-based application designed to help users efficiently organize and track their tasks. Whether you're working on personal projects, managing a team, or handling daily chores, this application simplifies the task management process.



Features:-

Create Tasks: Easily add new tasks with details such as title, description, and status.
Update Task Status: Track the progress of tasks by marking them as "Pending" or "Completed."
Edit Task Details: Modify task titles, descriptions, and statuses as needed.
Delete Tasks: Remove tasks that are no longer relevant or completed.
User-Friendly Interface: Intuitive and clean design for a seamless user experience.
Responsive Design: Access the application on various devices, including desktops, tablets, and mobile phones.


Usage:-
Create a Task:
Click on the "Create Task" button.
Fill in the title, description, and select the status.
Click "Submit" to add the task.


Update Task Status:
View the list of tasks and their current statuses.
Click on the "Edit" button to update the task details.
Select the new status and save the changes.


Edit Task Details:
Locate the task you want to edit.
Click on the "Edit" button.
Modify the title, description, or status and save the changes.


Delete a Task:
Find the task you wish to delete.
Click on the "Delete" button to remove the task.


Responsive Design:
Access the application from any device.
Enjoy a consistent and user-friendly experience.
Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: Django Rest Framework
Database: SQLite

API :-  RESTful API for seamless communication between frontend and backend.
This Task Management Project is designed to streamline your task organization process and enhance productivity.

Note :- All necessary file in the requrements.txt please check and install before run this project.


Here's a step-by-step guide to create a Django project, set up a virtual environment, and run the project.

Step:- 1
pip install django

Step:- 2
django-admin startproject task_managment

Step:- 3
cd task_management

Step:- 4
python -m venv venv

Step:- 5
source venv/bin/activate

Step:- 6
pip install django

Step:- 7
pip install -r requirements.txt

Step:- 8
python manage.py startapp tasks

Step:- 9
python manage.py makemigrations

Step:- 10
python manage.py migrate

Step:- 11
python manage.py createsuperuser

Step:- 12
python manage.py runserver

Step:- 13
Visit http://127.0.0.1:8000/ in your browser to see your Task Management application.


