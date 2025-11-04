🎟️ Sportify – Event Management Web Application

A Flask-based event management platform for creating, booking, and exploring events.

👥 Authors

Mutahher Naseer, Justin Lee, Kalifin Foot, and A. Garg
Developed for IAB207 Web Application Design (Group 28)

🧩 Overview

Sportify is a full-stack Flask web application that allows users to manage, view, and participate in events.
Users can:

Register and log in securely

Create, edit, and delete their own events

Book available events and view their booking history

Filter events by category or availability

Add comments and interact through event pages

Automatically update event status based on capacity or time

The app combines a clean Bootstrap front-end with a robust Flask + SQLAlchemy backend for smooth user experience and maintainable code.

⚙️ Technologies Used

Layer	Tools / Libraries
Frontend	HTML, CSS (Bootstrap), WTForms
Backend	Flask, Flask-Login, Flask-Bcrypt, Werkzeug
Database	SQLite (SQLAlchemy ORM)
Utilities	Email Validator, Bootstrap-Flask

🚀 Installation & Setup

1. Clone the repository
```bashgit clone https://github.com/Vivid809/IAB207_A3.git
cd IAB207_A3
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Initialize the database
```bashpython create_db.py
```
4. Run the Flask application
```bash
python main.py
```

Then open your browser and go to:
👉 http://127.0.0.1:5000/
