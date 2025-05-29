
# 🏫 Attendance Management System - Django

A web-based Attendance Management System built using **Django**. This system is designed to manage student attendance efficiently for educational institutions.

---

## 🚀 Features

- 🧑‍🏫 Admin panel for managing staff, students, and subjects
- 📅 Record and track student attendance by date and subject
- 📈 Attendance reports for each student
- 🧾 Pre-built authentication and permissions via Django admin
- 📁 SQLite support for quick setup

---

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Database**: SQLite
- **Frontend**: HTML/CSS (via Django templates)

---

## 📁 Project Structure

```

Attendance-Management-System/
│
├── manage.py
├── db.sqlite3
├── requirements.txt
├── CollegeERP/              # Main project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── attendance/              # Core attendance functionality
├── models.py
├── views.py
├── templates/
└── admin.py

````

---

## ⚙️ Installation & Setup

1. **Clone the Repository**
```bash
git clone https://github.com/itzmevig/ATTENDANCE-MANAGEMENT-SYSTEM.git
cd ATTENDANCE-MANAGEMENT-SYSTEM
````

2. **Navigate into the source directory**

```bash
cd "SourceCode/Attendance-Management-System-Django-Source-Code/Attendance Management System Django Source Code"
```

3. **Create a virtual environment**

```bash
python -m venv env
source env/bin/activate      # On Windows use `env\Scripts\activate`
```

4. **Install dependencies**

```bash
pip install -r requirements.txt
```

5. **Run the development server**

```bash
python manage.py runserver
```

6. **Access the application**
   Visit `http://127.0.0.1:8000/` in your browser.

---

## 🔑 Default Admin Credentials

> You may need to create a superuser if not already present:

```bash
python manage.py createsuperuser
```

---

## 🧑‍💻 Author

**Vignesh**
📂 [GitHub](https://github.com/itzmevig)

---

## ⭐ Contributions

If you'd like to contribute:

1. Fork this repo
2. Create a new branch
3. Submit a pull request!

Don’t forget to ⭐ star the repo if you find it useful!
