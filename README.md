# Flask To-Do App

![Flask Logo](flask_logo.jpg)

## Overview

This is an advanced Flask application implementing a To-Do list with CRUD operations. The app uses Flask-SQLAlchemy for database management, allowing users to add, complete, and delete tasks.

## Features

- **SQLite Database:** Tasks are stored in an SQLite database.
- **CRUD Operations:** Add, complete, and delete tasks.
- **Web Interface:** Simple and responsive web interface.

## How to Run

1. Make sure you have Python installed on your system.
2. Install Flask and Flask-SQLAlchemy using `pip install flask Flask-SQLAlchemy`.
3. Run the script `app.py`.
4. Open a web browser and go to [http://localhost:5000](http://localhost:5000) to access the To-Do app.

## Project Structure

- **app.py:** Main Flask application file.
- **templates/index.html:** HTML template for rendering tasks.
- **tasks.db:** SQLite database file.

## Dependencies

- Flask
- Flask-SQLAlchemy

## Usage

- View tasks on the homepage.
- Add a new task using the form.
- Complete or delete tasks using the provided links.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
