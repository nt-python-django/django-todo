# 📝 Django Todo App

A simple Todo application built with **Django 5.2**.  
Users can register, log in, and manage their tasks with basic CRUD operations.

---

## 🚀 Features

- ✅ User registration and login
- ✅ Create, read, update, and delete todos
- ✅ Mark todos as completed
- ✅ Default todos available for all users
- ✅ Timestamp for creation and updates

---

## 💻 Installation

1. **Clone the repository**:

```bash
git clone https://github.com/yourusername/django-todo.git
cd django-todo
````

2. **Create and activate a virtual environment**:

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. **Install dependencies**:

```bash
pip install -r requirements.txt
```

4. **Apply migrations**:

```bash
python manage.py migrate
```

5. **Create a superuser (optional, for admin panel)**:

```bash
python manage.py createsuperuser
```

6. **Run the development server**:

```bash
python manage.py runserver
```

Open your browser at [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to see the app in action.

---

## 📝 Usage

1. Register a new user or log in.
2. Access the Todo list.
3. Add new todos.
4. Edit or delete existing todos.
5. Mark todos as completed.

---

## 🛠️ Tech Stack

* Python 3.13
* Django 5.2
* HTML, CSS (Bootstrap optional)
* SQLite/PostgreSQL

---