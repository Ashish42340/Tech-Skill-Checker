# Tech Skills Checker 🚀

A smart Flask-based web application that helps users check, manage, and analyze their technical skills.

The system helps students, beginners, and job seekers understand their current skills and compare them with industry requirements.

---

# 📌 Project Overview

Tech Skills Checker is a web application developed using Python Flask.

The application allows users to:

* Create account
* Login securely
* Add technical skills
* Track skill levels
* Analyze job requirements
* Get job recommendations
* Compare skills with market demands

This project is useful for:

* Students
* Freshers
* Developers
* Job seekers
* Learners

---

# ✨ Features

## 🔐 User Authentication

Users can:

* Register account
* Login securely
* Logout safely
* Manage sessions

---

## 💻 Skill Management

Users can:

* Add technical skills
* Update skills
* Delete skills
* Set proficiency levels

Example:

* Python → Intermediate
* SQL → Beginner
* React → Advanced

---

## 📊 Skill Analysis

The system analyzes:

* User skill strength
* Missing skills
* Skill gap
* Skill categories

---

## 💼 Job Recommendation

The application recommends jobs based on:

* User skills
* Match percentage
* Skill relevance

---

## 📱 Responsive Design

* Mobile friendly
* Modern UI
* Easy navigation
* Fast loading

---

# 🛠 Technologies Used

## Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

---

## Backend

* Python
* Flask

---

## Database

* SQLite
* MySQL (optional)

---

## Additional Tools

* Jinja Templates
* Flask Session
* REST APIs (optional)

---

# 📂 Project Structure

```bash
Tech-Skills-Checker/
│
├── app.py
├── requirements.txt
├── render.yaml
├── README.md
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── skills.html
│   └── jobs.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   └── script.js
│   │
│   └── images/
│
├── routes/
├── models/
├── database/
└── utils/
```

---

# ⚙️ Installation Guide

## Step 1 — Clone Repository

```bash
git clone <repository-link>
```

---

## Step 2 — Open Project Folder

```bash
cd Tech-Skills-Checker
```

---

## Step 3 — Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Step 4 — Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 📦 requirements.txt

```txt
Flask
Flask-SQLAlchemy
Flask-Login
Werkzeug
gunicorn
```

---

## Step 5 — Run Application

```bash
python app.py
```

---

## Step 6 — Open Browser

```bash
http://127.0.0.1:5000
```

---

# 🌐 Deployment Guide

This project is a Flask application.

GitHub Pages does not support Flask backend.

Use platforms like:

* Render
* Railway
* PythonAnywhere

for deployment.

---

# 🚀 Deploy on Render

## Step 1

Upload project to GitHub.

---

## Step 2

Create `render.yaml`

```yaml
services:
  - type: web
    name: tech-skills-checker
    env: python
    buildCommand: "pip install -r requirements.txt"
    startCommand: "gunicorn app:create_app()"
```

---

## Step 3

Push code:

```bash
git add .
git commit -m "deploy"
git push
```

---

## Step 4

Connect GitHub repository with Render.

---

## Step 5

Deploy project.

---

# 📊 How The System Works

## Step 1

User registers account.

---

## Step 2

User logs into dashboard.

---

## Step 3

User adds technical skills.

---

## Step 4

Application analyzes user skills.

---

## Step 5

System compares skills with jobs.

---

## Step 6

User gets recommendations.

---

# 📈 Future Improvements

Future updates may include:

* AI-based recommendations
* Resume analyzer
* Interview preparation
* Learning roadmap
* Real-time job APIs
* LinkedIn integration
* Skill certification system

---

# 🎯 Advantages

* Easy to use
* Beginner friendly
* Useful for students
* Real-world project
* Good portfolio project
* Helps in career planning

---

# 🧠 Learning Outcomes

By building this project, developers can learn:

* Flask framework
* Frontend integration
* Backend development
* Database management
* User authentication
* Deployment process
* API handling

---

# 👨‍💻 Author

Ashish Kumar

---

# 📜 License
