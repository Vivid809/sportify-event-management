🎟️ Sportify – Event Management Web Application

A Flask-based event management platform for creating, booking, and exploring events.

👥 Authors

Mutahher Naseer, Justin Lee, Kalifin Foot, and A. Garg
Developed for IAB207 Web Application Design(QUT) (Group 28)

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
```bash
git clone https://github.com/Vivid809/IAB207_A3.git
cd IAB207_A3
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Initialize the database
```bash
python create_db.py
```
4. Run the Flask application
```bash
python main.py
```

Then open your browser and go to:
👉 http://127.0.0.1:5000/

🧠 Key Features

✅ User authentication and role-based access
✅ Event creation, editing, and deletion
✅ Category-based event filtering
✅ Real-time event status updates (Open, Sold Out, Inactive)
✅ Comment system for user interaction
✅ Booking system with capacity checks
✅ Booking history view for users
✅ Responsive and mobile-friendly UI

🗂️ Repository Structure
```bash
IAB207_A3/
├── Sportify/                   # Main Flask application package
│   ├── static/                 # CSS, JS, and static assets
│   ├── templates/              # HTML templates using Bootstrap
│   ├── __init__.py             # Flask app factory and configuration
│   ├── auth.py                 # Handles user login, registration, and authentication
│   ├── event.py                # Event creation, editing, and booking routes
│   ├── forms.py                # WTForms classes for user input validation
│   ├── models.py               # SQLAlchemy database models
│   └── views.py                # Core routes for homepage and general pages
│
├── instance/                   # Database folder (auto-created by Flask)
│   └── sitedata.sqlite         # SQLite database file
│
├── create_db.py                # Script to initialize and seed the database
├── main.py                     # Entry point to run the application
├── output.txt                  # Optional output log or debugging file
├── requirements.txt            # Python dependencies list
├── .gitignore                  # Files and folders excluded from git
└── README.md                   # Project documentation

```

💡 Future Improvements

Add admin dashboard for event moderation

Implement notification emails for bookings

Integrate Google Maps API for event locations

Enhance UI/UX with interactive calendar views

⚠️ Deployment Notice

This project currently runs locally via Flask and SQLite for demonstration and educational purposes.
No active server deployment is maintained — setup instructions above replicate the development environment.

## 📫 Contact

- **Email:** [mutahhar.you@gmail.com](mailto:mutahhar.you@gmail.com)  
- **LinkedIn:** [Mutahher Naseer](https://www.linkedin.com/in/mutahher-naseer-30778b220)

