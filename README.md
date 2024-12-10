# Django CRUD Application

This is a simple Django CRUD (Create, Read, Update, Delete) application that allows users to manage a list of students. The application includes basic operations like adding, viewing, updating, and deleting student records, along with a user-friendly interface built using Bootstrap.

## Features

- **Create**: Add new student records.
- **Read**: View all student records.
- **Update**: Modify existing student information.
- **Delete**: Remove student records from the database.

## Requirements

- Python 3.x
- Django 3.x or later
- Bootstrap for front-end styling

## Installation

### Step 1: Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/your-username/django-crud-app.git

Step 2: Install Dependencies
Navigate to the project directory and install the necessary dependencies:

bash
Copy code
cd django-crud-app
pip install -r requirements.txt
Note: If you don't have a requirements.txt file, you can create one using pip freeze > requirements.txt.

Step 3: Set Up the Database
Run the following command to apply the database migrations:

bash
Copy code
python manage.py migrate
Step 4: Create a Superuser (Optional)
If you want to access the Django admin interface, you can create a superuser account:

bash
Copy code
python manage.py createsuperuser
Follow the prompts to set up the username, email, and password.

Step 5: Run the Development Server
Start the Django development server:

bash
Copy code
python manage.py runserver
You can now access the application by navigating to http://127.0.0.1:8000/ in your web browser.

Usage
Add a New Student
Click the "Add New Student" button.
Fill in the student's name and email.
Click Add New Student to save the new student.
View Students
The home page will display a table with a list of all students. You can view their names and emails.

Update Student Information
Click the Edit (pencil) button next to a student.
Modify the student's name or email.
Click Update to save changes.
Delete a Student
Click the Delete (trash bin) button next to a student.
Confirm the deletion to remove the student.
Directory Structure
markdown
Copy code
django-crud-app/
├── crudapp/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   ├── templates/
│   │   ├── index.html
│   └── urls.py
├── db.sqlite3
├── manage.py
├── requirements.txt
└── settings.py
crudapp/: The main app containing the models, views, and templates.
index.html: The template for displaying and interacting with the student records.
requirements.txt: A file that lists all the required Python packages.
Contributing
If you’d like to contribute to this project, feel free to fork the repository, make your changes, and submit a pull request.

License
This project is open-source and available under the MIT License. See the LICENSE file for more information.

Acknowledgments
Thanks to Bootstrap for providing the front-end framework.
Django for making web development faster and easier.
