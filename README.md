# Django To-Do List with User Authentication

This is a simple To-Do List application built with Django, featuring user authentication. Users can register, log in, create tasks, update tasks, delete tasks, and filter tasks by title.

## Features

- User registration and authentication
- Create, read, update, and delete tasks
- Filter tasks by title
- Mark tasks as complete or incomplete
- User-specific task management

## Technologies Used

- Django
- SQLite (default database)
- HTML/CSS for front-end templates

## Installation

### Prerequisites

Make sure you have Python and pip installed. You can download Python from [python.org](https://www.python.org/downloads/).

### Clone the Repository

```bash
git clone https://github.com/steve-ongera/Django-To-Do-list-with-user-authentication-.git
cd django-to-do-list
```


### Set Up a Virtual Environment
It's a good practice to use a virtual environment. You can set it up as follows:


python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

### Install Dependencies
Install the required packages using pip:
pip install django

### Configure the Project
Navigate to the project directory.
Run the following commands to create migrations and apply them:

python manage.py makemigrations
python manage.py migrate

### Create a superuser for the admin panel (optional):
python manage.py createsuperuser

### Run the development server:

python manage.py runserver
Open your browser and go to http://127.0.0.1:8000/ to view the application.

### Usage
Register: Go to /register/ to create a new account.
Login: Use /login/ to log into your account.
Task Management: After logging in, you can create, view, update, and delete tasks.
Filter Tasks: Use the search bar to filter tasks by title.

### Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request.

### License
This project is licensed under the MIT License.

### Acknowledgments
Django Documentation
Bootstrap for styling (if used in templates)


### How to Use

1. Replace `https://github.com/yourusername/django-to-do-list.git` with the actual URL of your repository.
2. Modify the technologies and any other sections based on any additional features or libraries you've used.
3. Feel free to add or remove sections based on your specific project needs.

This `README.md` provides a clear overview of the project, making it easier for others to unde