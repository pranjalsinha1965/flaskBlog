# flaskBlog
Build a starter flask web application. Try to embedd all the features of a blog application !

## Flask Blog – Basic Authentication Forms
This project is a simple Flask web application that includes user registration and login functionality using Flask-WTF and WTForms.

## 🚀 Features
User Registration Form
User Login Form
Form validation using WTForms
Email validation support
Runs on Flask development server

## 📁 Project Structure
```cpp
Copy code
Flask_Blog/
│── flaskblog.py
│── forms.py
│── templates/
│── static/
```

🛠 Setup Instructions

### 1️⃣ Install dependencies

```bash
Copy code
pip install flask flask-wtf wtforms email_validator
2️⃣ Set the Flask application
(MINGW64 / Git Bash)
```

```bash
Copy code
export FLASK_APP=flaskblog.py
```

### 3️⃣ Run the development server

```bash
Copy code
flask run
``` 

### 🧩 Forms Included
Registration Form
Username
Email
Password
Confirm Password
Login Form
Email
Password
Remember Me

### 🐞 Common Fixes Applied
Corrected validator usage: DataRequired() instead of DataRequired

Installed missing package: email_validator

Set FLASK_APP correctly (no spaces around =)

### ✅ Status
Basic application setup and routing functional.
Ready for extension into a complete blog platform.

### HTML 
1. [Bootstrapped Starter Files](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
2. [starter code sidebar, static/main.css](https://github.com/CoreyMSchafer/code_snippets/tree/master/Python/Flask_Blog)



