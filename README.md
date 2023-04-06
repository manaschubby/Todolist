# Todolist
A simple To-do list web-app using Flask and SQLAlchemy

## Usage

To install Todolist, you will need to have Python 3.x and pip installed on your system. Once you have these prerequisites, follow these steps:

- Clone the repository using the following command:
```bash
git clone https://github.com/manaschubby/Todolist.git
```

- Navigate to the Todolist directory:
```bash
cd Todolist
```

- Create and run the virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate
```

- Run the following commands to install all the required dependencies in a virtual environment

```bash
pip install -r requirements.txt
```

- Now run the following command to start the server

```bash
python app.py
```


### Navigate to `localhost:5000/` to view your Tasks. Add, update and delete your tasks using the given fields.


## Technologies used:
### - Flask: 
Flask is a lightweight web framework for Python. It provides a simple and flexible way to build web applications. Flask is used in Todolist to handle HTTP requests, manage sessions, and render HTML templates.

### - SQLite:
SQLite is a simple and efficient relational database. It is used in Todolist to store and manage the tasks. SQLite is a serverless database, which means that it doesn't require a separate server process to be running. This makes it easy to use and deploy.

### - Flask-SQLAlchemy: 
Flask-SQLAlchemy makes it easy to connect Flask applications to relational databases, such as PostgreSQL, MySQL, SQLite, and others. It provides a high-level interface for creating database models, executing SQL queries, and managing database transactions.
