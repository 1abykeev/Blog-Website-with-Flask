# 📝 Flask Blog Website

A full-featured blog website built using **Flask**, **Bootstrap 5**, **Flask-WTF**, **Flask-Login**, **Flask-CKEditor**, and **SQLite**.

This app allows users to register, log in, create, edit, delete, and comment on blog posts.

---

## 🚀 Features

- ✅ User authentication (Register / Login / Logout)
- ✅ Admin-only access to create, edit, and delete posts
- ✅ Rich-text editing with CKEditor
- ✅ Comment system (only for logged-in users)
- ✅ User avatars using Gravatar
- ✅ Responsive Bootstrap 5 UI

---

## 🧱 Tech Stack

- Python 3.11+
- Flask
- Bootstrap-Flask
- Flask-WTF
- Flask-Login
- Flask-CKEditor
- Flask-Gravatar
- SQLite (SQLAlchemy ORM)

---

## 🖥️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/blog-flask-app.git
cd blog-flask-app

## 2 Create and activate a virtual environment

# Create virtual environment
python -m venv venv

# Activate it
# Windows
venv\Scripts\activate

# macOS/Linux
source venv/bin/activate

## 3 Install dependencies

``` pip install -r requirements.txt


## 4. Set environment variables

# Create a .env file in the root directory and add:

FLASK_KEY=your_secret_key
DB_URI=sqlite:///posts.db

## 5. Run the application

``` python -m flask --app main.py --debug run
