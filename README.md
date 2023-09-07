## Flask_task_master


## Description

The Task Master Flask App is a web-based task management application built with Flask, a Python web framework. It allows users to create, view, update, and delete tasks, helping them stay organized and productive.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation

To run the Task Master Flask App locally, follow these steps:

1. Clone the repository:

   ```shell
   git clone https://github.com/shafaq12/flask- task-master.git
   cd flask-task-master
   ```

2. Create a virtual environment (optional but recommended):

   ```shell
   python -m venv venv
   ```

3. Activate the virtual environment:

   - Windows:

     ```shell
     venv\Scripts\activate
     ```

   - macOS and Linux:

     ```shell
     source venv/bin/activate
     ```

4. Install the project dependencies:

   ```shell
   pip install -r requirements.txt
   ```

5. Create the database tables:

   ```shell
   python db_create.py
   ```

6. Run the Flask application:

   ```shell
   python app.py
   ```

The app will be accessible at `http://localhost:5000` in your web browser.

## Usage

### Create a New Task

1. Click the "Add Task" button.
2. Enter the task details in the form.
3. Click the "Submit" button.

### View and Manage Tasks

- The app's homepage displays a list of tasks.
- Click on a task to view its details.
- Use the "Delete" and "Update" links to manage tasks.

### Screenshots
![image](https://github.com/shafaq12/flask_task_master/assets/87670845/90a826d9-3ce8-4c3b-a02a-f13f8550034e)
![image](https://github.com/shafaq12/flask_task_master/assets/87670845/2e7a864f-69bd-4041-b58a-42ae61ed829f)




## Features

- User-friendly interface for managing tasks.
- CRUD (Create, Read, Update, Delete) operations for tasks.


## Contributing

Contributions to the Task Master Flask App are welcome! If you'd like to contribute:

1. Fork the repository on GitHub.
2. Clone the forked repository to your local machine.
3. Create a new branch for your feature or bug fix.
4. Make your changes and commit them.
5. Push your changes to your fork on GitHub.
6. Create a pull request from your fork to the main repository.
