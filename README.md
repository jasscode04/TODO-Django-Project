
# MY TODO Project (Django Web App)

A Django-based Todo Web Application that allows users to sign up, log in, and manage their personal task lists.

---

## 🌟 Features

- User authentication (Sign up, Login)
- Add, edit, and delete todos
- Task completion tracking
- Responsive and clean UI
- SQLite3 as the default database

---

## 📁 Project Structure

```
MY TODO Project/
├── README.md
├── todo/
│   ├── db.sqlite3                # SQLite database
│   ├── manage.py                 # Django project manager
│   ├── todo/                     # Main Django application
│   │   ├── admin.py
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── urls.py
│   │   ├── settings.py
│   │   ├── templates/            # HTML templates
│   │   │   ├── signup.html
│   │   │   ├── loginn.html
│   │   │   ├── todo.html
│   │   │   └── edit_todo.html
│   │   ├── static/               # CSS and JavaScript
│   │   │   ├── css/
│   │   │   │   ├── styles.css
│   │   │   │   └── index.css
│   │   │   └── js/
│   │   │       └── todo.js
│   │   ├── migrations/
│   │   │   └── 0001_initial.py
```

---

## ⚙️ Getting Started

### Prerequisites

- Python 3.x
- Django (install via pip)

### Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone <your-repo-url>
   cd "MY TODO Project/todo"
   ```

2. **Create a Virtual Environment (Optional but Recommended)**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install Dependencies**

   ```bash
   pip install django
   ```

4. **Run Migrations**

   ```bash
   python manage.py migrate
   ```

5. **Run the Server**

   ```bash
   python manage.py runserver
   ```

6. **Open in Browser**

   Navigate to `http://127.0.0.1:8000/`

---

## 🧩 App Overview

- `signup.html`, `loginn.html`: User registration & login
- `todo.html`: Displays the list of todos
- `edit_todo.html`: Edit an existing todo
- `todo.js`: JS interactivity
- `styles.css`, `index.css`: Styling

---

## 📬 Contact

Created by **Jasprit Singh Sanu**  
📧 jaspritsinghsanu@gmail.com
