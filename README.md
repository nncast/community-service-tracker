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
- Promote students and handle graduation

**Student/Staff Functions**
- Secure login with password hashing
- View personal attendance records
- Search and filter events
- Access downloadable attendance reports

## Technologies Used
- Python 3.11+
- Flask
- HTML, CSS, JavaScript
- SQLite
- Flask-SQLAlchemy
- Flask-Migrate
- Werkzeug

## Requirements
- Python 3.11+  
  [Download Python](https://www.python.org/downloads/)  
- Flask  
  ```bash
  pip install Flask
