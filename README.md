# Flask To-Do Web Application

## Project Overview
This project is a simple and intuitive web-based task manager built using Python Flask. It allows users to add, mark as complete, and delete tasks. Each task is stored persistently using SQLite. The UI is styled with Bootstrap for a clean and responsive experience.
This project was developed as part of the internship at Infotact Solutions.

## Features
- Add new tasks through a user-friendly form
- Mark tasks as completed with a single click
- Delete tasks instantly
- Stores data using a local SQLite database
- Auto-creates the database and table on first run
- Styled using Bootstrap for a clean interface
- Lightweight and runs locally in the browser

## Tech Stack
- Language: Python 3.x
- Framework: Flask
- Database: SQLite
- Frontend: HTML, Jinja2 templates, Bootstrap 5
- Others: SQL, Routing, Form handling

## How It Works
The Flask To-Do app uses a simple app.py script to manage routes and logic. It renders the task list from an SQLite database. When a user submits a new task, it’s inserted into the database. Tasks can also be marked as complete or deleted. Flask handles routing, and HTML templates display the task list using Jinja2. On first run, the database is automatically initialized if it doesn't exist.

## How to Use
1. Clone or download this repository.
2. Open terminal and navigate to the project folder.
3. Install Flask (if not already installed):
    pip install flask
4. Run the application:
    python app.py
5. Open your browser and go to:
    http://127.0.0.1:5000/
6. Use the app to:
   - Add tasks
   - Mark tasks as completed
   - Delete tasks
   
## Team Contributions
- Member 1: Flask app logic, routing, database integration
- Member 2: Frontend UI, HTML + Bootstrap styling
- Member 3: Testing, review, error handling
- Member 4: Documentation, screenshots, demo guide
