# Community Service Tracker  
(2025)

**Community Service Tracker** is a Flask-based web application designed to help IT students and administrators track community service participation.  
It provides tools for event management, student management, attendance logging, hour computation, and user authentication.  
The official project repository is available here: [Community Service Tracker GitHub](https://github.com/nncast/community-service-tracker)

## Features

**Admin Functions**
- Manage user accounts with role-based access (admin, staff)
- Add, edit, and remove students, including year level and academic year
- Create, update, and delete events with semester and year level targeting
- Track student attendance including time-in, time-out, and total hours
- View attendance history and log manual adjustments
- Export attendance reports as CSV filtered by student, academic year, semester, or event
- Manage academic years and semesters
- Promote/Enroll students and handle graduation

**Student/Staff Functions**
- Secure login with password hashing
- Add, view, and edit attendance records
- Search and filter events
- Access downloadable attendance reports

## Technologies Used
- Python 3.11+ (v3.11 recommended)
- Flask
- HTML, CSS, JavaScript
- SQLite

## Requirements
- Python 3.11+  
  [Download Python](https://www.python.org/downloads/)  
- Flask  
  ```bash
  pip install Flask
- Flask-SQLAlchemy  
  ```bash
  pip install Flask-SQLAlchemy
- Flask-Migrate  
  ```bash
  pip install Flask-Migrate
- Flask-Migrate  
  ```bash
  pip install Werkzeug

## Installation
1. Clone the repository or download the project files:
   ```bash
   git clone https://github.com/nncast/community-service-tracker.git
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/macOS
   venv\Scripts\activate      # Windows

3. Install required packages:
   ```bash
   pip install -r requirements.txt
4. Initialize the database:
   ```bash
   flask db init
   flask db migrate
   flask db upgrade
5. Run the application:
   ```bash
   python app.py
6. Open a browser and go to http://127.0.0.1:5000 to access the dashboard.

## Default Login Credentials
- **Username:** admin
- **Password:** admin123



**Developers:**
- Kimberly Bernabe
- Janelle Ann Castillo
- Hazel Sebastian
- Louisse Glaze Villarente
