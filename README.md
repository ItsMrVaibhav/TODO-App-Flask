# TODO App using Flask
A simple TODO app built using Flask. The application supports adding todos, updating existing todos, deleting or marking them as done, and filtering todos.

## Setup
Follow the instructions below to setup the project.
1. Open the terminal or command prompt.
2. Type `virtualenv env` to create a virtual environment.
3. Type `env\Scripts\active` to activate the environment on Windows.
4. Type `pip install -r requirements.txt` to install the dependencies.
5. Type `python app.py` to start the Flask application.

## Create Database
Follow the instructions below to create the database.
1. Open the terminal or command prompt.
2. Type `python` to run the Python interactive shell.
3. Type the following to create the database.
    ```python
    from app import db
    db.create_all()
    ```
4. Type `exit()` to exit the shell.