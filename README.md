Django To-Do List Project Documentation
Introduction

This project is a to-do list application built using Django, which allows users to log in, create new users, view tasks with status for each user, search tasks, and perform CRUD (create, read, update, delete) operations on tasks.  

**Requirements**

follow requirements.txt file

**Installation**

    Create a new Django project using the following command:
    django-admin startproject todolist

**Create a new Django app for the to-do list**

    python manage.py startapp app_name

**Models**

The following models are used in this project:

    User (Django built-in model)
    Task

User Model

The User model is the built-in Django model for authentication and authorization. It is used to manage user authentication and authorization in the project.

**Task Model**

The Task model is used to manage tasks in the project. It has the following fields:

    title (CharField)
    description (TextField)
    status (BooleanField)
    created_at (DateTimeField)
    user (ForeignKey to User model)

**Views**

The following views are used in this project:

    LoginView (Django built-in view)
    SignUpView (Django built-in view)
    TaskListView
    TaskDetailView
    TaskCreateView
    TaskUpdateView
    TaskDeleteView

**LoginView**

The LoginView is the built-in Django view for user authentication. It handles user authentication and redirects users to the task list page upon successful login.

**SignUpView**

The SignUpView is the built-in Django view for creating new users. It allows users to create new accounts and redirects them to the task list page upon successful sign up.

**TaskListView**

The TaskListView displays a list of tasks for each user. It allows users to filter tasks based on their status (completed or not completed).

**TaskDetailView**

The TaskDetailView displays the details of a task, including its title, description, and status.

**TaskCreateView**

The TaskCreateView allows users to create new tasks and adds them to the task list.

**TaskUpdateView**

The TaskUpdateView allows users to update existing tasks and save changes to the task list.

**TaskDeleteView**

The TaskDeleteView allows users to delete tasks from the task list.
URLs

**The following URLs are used in this project:**

    Login URL (Django built-in URL)
    Sign Up URL (Django built-in URL)
    Task List URL
    Task Detail URL
    Task Create URL
    Task Update URL
    Task Delete URL

**The following templates are used in this project:**

    Login template (Django built-in template)
    Sign Up template (Django built-in template)
    Task List template
    Task Detail template
    Task Create template
    Task Update template
    Task Delete template

**Conclusion**

This Django project provides a complete solution for managing tasks with the opportunity for user authentication, creation of new users, display
