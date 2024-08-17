# Django To-Do List Application

This is an interactive and feature-rich To-Do list application built with Django. Users can create, manage, and track their tasks easily.

## Features


- **Task Management**: Create, edit, delete, and mark tasks as completed.
- **Interactive UI**: A responsive and user-friendly interface for easy task management.


## Installation

### Prerequisites

- Python 3.x
- Django
- Git

### Clone the Repository

```bash
git clone https://github.com/gmgowrish/Django_ToDoList.git
cd Django_ToDoList
```

### Create a Virtual Environment

Create a virtual environment to manage dependencies:

```bash
python3 -m venv venv
```

Activate the virtual environment:

- **For Windows**:
  ```bash
  venv\Scripts\activate
  ```
- **For macOS/Linux**:
  ```bash
  source venv/bin/activate
  ```

### Install Dependencies

Install the required packages using `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Database Setup

Run migrations to set up the database:

```bash
python manage.py migrate
```

### Create a Superuser

Create a superuser to access the Django admin:

```bash
python manage.py createsuperuser
```

### Run the Server

Start the development server:

```bash
python manage.py runserver
```

Open your browser and go to `http://127.0.0.1:8000/` to see the application.

## Usage

- **Dashboard**: Access your tasks and manage them easily from the dashboard.
- **Create Task**: Add new tasks with details such as title, description, priority, and deadline.
- **Manage Tasks**: Edit, delete, or mark tasks as completed directly from the dashboard.
- **Search and Filter**: Use the search bar and filters to quickly find specific tasks.
- **Profile**: Update your profile information and manage your account settings.

## Contributing

Feel free to contribute to this project by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.

---
