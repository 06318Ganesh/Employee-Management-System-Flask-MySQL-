# Employee-Management-System-Flask-MySQL-
Employee Management System (Flask + MySQL)

A fully functional Employee Management System built using Flask, MySQL, and Jinja2, designed with clean architecture, secure authentication, and role-based access control.
This project demonstrates end-to-end backend development skills with a professional folder structure, CRUD operations, secure password hashing, and responsive UI integration.

📌 Features
🔐 Role-Based Authentication

Secure login system for Admin and Employee

Passwords encrypted using bcrypt hashing

Session management using Flask sessions

🧑‍💼 Admin Functionalities

View all employees

Add new employees

Manage employee roles

View employee details

Fully controlled dashboard

👨‍🔧 Employee Functionalities

Secure login

Personalized employee dashboard

View profile information

Update basic details (optional extension)

🗂️ Project Structure
employee_management_system_full/
│── app.py
│── db.py
│── init_db.sql
│── requirements.txt
│── .env.example
│── static/
│   └── css/
│── templates/
│   ├── index.html
│   ├── admin_dashboard.html
│   ├── add_employee.html
│   ├── employee_dashboard.html
│   └── employee_profile.html
└── venv/ (ignored)

🏗️ Tech Stack
Backend

Python (Flask)

MySQL (Relational Database)

Jinja2 Template Engine

Bcrypt for password hashing

Frontend

HTML5, CSS3

Jinja2 templating

Responsive UI Pages

🔧 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/06318Ganesh/employee-management-system.git
cd employee-management-system

2️⃣ Create a virtual environment
python -m venv venv


Activate it:

Windows

venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Create MySQL Database

Import the SQL schema:

SOURCE init_db.sql;

5️⃣ Configure environment variables

Create a .env file:

MYSQL_HOST=localhost
MYSQL_USER=root
MYSQL_PASSWORD=yourpassword
MYSQL_DB=employee_system
SECRET_KEY=your_secret_key

6️⃣ Run the application
python app.py


App will run at:

http://127.0.0.1:5000/

🔐 Default Login Credentials
Admin Login
Employee ID: ADMIN001
Password: admin123
Role: admin

Sample Employee Login
Employee ID: EMP001
Password: rohan123
Role: employee


<img width="1920" height="1080" alt="Screenshot (156)" src="https://github.com/user-attachments/assets/dfa846de-71f4-447e-a20d-ce5bd2da95e3" />
<img width="1920" height="1080" alt="Screenshot (155)" src="https://github.com/user-attachments/assets/1b6f6649-58a1-4db0-8d71-b787899d33ff" />
<img width="1920" height="1080" alt="Screenshot (154)" src="https://github.com/user-attachments/assets/a4fdab63-c339-4ff4-8ebe-5be62aa72300" />



🧪 Highlights & Best Practices

✔ Secure password hashing using bcrypt
✔ Clean separation of routes, templates, and DB logic
✔ Error-handling and safe redirects
✔ Environment variable support using python-dotenv
✔ Database-driven authentication
✔ Well-structured SQL schema with seed data

🚀 Future Enhancements

JWT-based API version

Leave request system

Department management

Employee attendance system

Deployment using Railway / Render

Admin analytics dashboard



