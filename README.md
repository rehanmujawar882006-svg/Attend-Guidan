# Attend-Guidan
Web-based attendance management system with separate Faculty, Student, and Admin login using Flask, HTML, CSS, Bootstrap, and MySQL.
Add the student ,admin page . 
the backend is used python flask,python fastAPI
the database sql.

Project Structure :-
Attend-Guidan/
│
├── app.py
├── create_user.py
├── schema.sql
├── requirements.txt
├── README.md
│
├── templates/
│   ├── login.html
│   │       Admin login
│   ├── admin_dashboard.html
│   ├── manage_faculty.html
│   ├── manage_students.html
|   |──manage class/div.html
|   |──manage lectures.html
|   |──manage batches.html
│   ├── admin_reports.html
│   │       Faculty 
│   ├── faculty_dashboard.html
│   ├── mark_attendance.html
│   ├── view_students.html
│   ├── faculty_reports.html
│   │       Student
│   ├── student_dashboard.html
│   ├── my_attendance.html
│   ├── my_profile.html
│   └── defaulter_status.html
│
└── static/
    │
    ├── css/
    │   ├── style.css
    │   ├── admin.css
    │   ├── faculty.css
    │   └── student.css
    │
    ├── js/
    │   └── script.js
    │
    └── images/
        └── logo.png