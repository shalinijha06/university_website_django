# Gyan Uday University — University Management Website

A full-stack **University Management Website** built with **Django** to provide a centralized platform for managing students, courses, attendance, fees, examinations, results, and other university-related information.

The project focuses on building a structured, role-based university portal with a clean and user-friendly interface.

## 🚀 Features

### 🔐 Accounts & Authentication

* User authentication and login system
* Secure access to protected pages
* Django-based user management
* Admin/superuser support

### 👨‍🎓 Student Management

* Add and manage student records
* View student information
* Organize students by academic details
* Student-focused dashboard functionality

### 📚 Course Management

* Create and manage courses
* Maintain course information
* Organize academic course data

### 📅 Attendance Management

* Record student attendance
* View attendance information
* Manage attendance records for students

### 💰 Fees Management

* Manage student fee records
* Track fee information
* View payment-related details
* Maintain structured fee data

### 📝 Examinations & Results

* Manage examination records
* Store student marks
* View examination results
* Display student performance information

### 📊 Dashboard

* Centralized university dashboard
* Quick access to major modules
* Overview of important university data

## 🛠️ Tech Stack

**Frontend**

* HTML5
* CSS3
* JavaScript
* Django Templates

**Backend**

* Python
* Django
* Django REST Framework

**Database**

* SQLite (development)

**Other Tools**

* Git
* GitHub
* Pillow
* python-decouple

## 📁 Project Structure

```text
gyan_uday/
│
├── accounts/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   └── urls.py
│
├── students/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   └── urls.py
│
├── courses/
│   ├── models.py
│   ├── views.py
│   └── urls.py
│
├── attendance/
│   ├── models.py
│   ├── views.py
│   └── urls.py
│
├── fees/
│   ├── models.py
│   ├── views.py
│   └── urls.py
│
├── results/
│   ├── models.py
│   ├── views.py
│   └── urls.py
│
├── dashboard/
│   ├── views.py
│   └── urls.py
│
├── templates/
│   └── ...
│
├── static/
│   └── ...
│
├── gyan_uday/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/shalinijha06/university_website_django.git
cd university_website_django
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply database migrations

```bash
python manage.py migrate
```

### 6. Create an admin/superuser account

```bash
python manage.py createsuperuser
```

Follow the instructions in the terminal to create the account.

### 7. Run the development server

```bash
python manage.py runserver
```

The website will be available at:

```text
http://127.0.0.1:8000/
```

## 🔑 Admin Panel

Django's built-in admin panel can be accessed through:

```text
http://127.0.0.1:8000/admin/
```

Log in using the superuser credentials created during setup.

## 📌 Main Modules

| Module       | Purpose                            |
| ------------ | ---------------------------------- |
| Accounts     | Authentication and user management |
| Dashboard    | Centralized overview of the system |
| Students     | Student record management          |
| Courses      | Course management                  |
| Attendance   | Student attendance management      |
| Fees         | Fee and payment record management  |
| Examinations | Examination management             |
| Results      | Marks and result management        |

## 🎯 Project Objectives

The main objectives of this project are to:

* Develop a centralized university management system.
* Digitize common academic and administrative processes.
* Provide organized management of student information.
* Simplify attendance, fees, courses, examinations, and results management.
* Build a scalable web application using Django.
* Practice backend development, database management, authentication, and Git-based version control.

## 🔮 Future Improvements

Possible future enhancements include:

* Student and faculty role-based dashboards
* Online fee payment integration
* Automated attendance reports
* PDF result generation
* Email notifications
* Advanced search and filtering
* REST API expansion
* Responsive mobile-first improvements
* Deployment with a production database
* Cloud hosting and CI/CD integration

## 📸 Screenshots


## 👩‍💻 Author

**Shalini Jha**

B.Tech — Computer Science & Engineering

GitHub: [@shalinijha06](https://github.com/shalinijha06)

## 📄 License

This project is developed for educational and portfolio purposes.
