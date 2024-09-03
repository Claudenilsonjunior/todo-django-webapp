# Todo Django Project

This is a simple to-do list application built with Django.

## Features

- User authentication (login/logout)
- Create, update, and delete tasks
- Mark tasks as completed

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/todo-django.git
    cd todo-django
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```bash
    python manage.py migrate
    ```

5. Run the development server:
    ```bash
    python manage.py runserver
    ```

## Usage

1. Go to `http://127.0.0.1:8000/` in your browser.
2. Create an account or log in.
3. Start managing your tasks!
