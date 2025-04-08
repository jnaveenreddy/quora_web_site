# Quora Clone 

A simple question-and-answer platform inspired by Quora. This project was built using the Django web framework and allows users to register, log in, ask questions, and view responses.


## Features

- User Registration and Login system (with authentication)
- Logged-in users can:
  - Ask new questions
  - View all questions
  - View individual question details
- Clean and responsive user interface using Bootstrap
- Navigation bar with authentication-based menu


## Project Structure
quora_clone/
├── core/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   ├── views.py
│   └── migrations/
│       ├── __init__.py
│       └── 0001_initial.py
│
├── quora_clone/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── templates/
│   ├── base.html
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── ask_question.html
│   └── question_detail.html
│
├── db.sqlite3
├── manage.py
└── requirements.txt


---

## Tech Stack

- **Backend**: Python, Django
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default Django DB)

---

## Getting Started

1. **Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/quora_clone.git
cd quora_clone

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate

python manage.py runserver

http://127.0.0.1:8000/

