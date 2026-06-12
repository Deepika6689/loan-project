# 💰 EasyLoan Finance Pvt Ltd — Loan Management System

## 🌟 About the Project

**EasyLoan Finance Pvt Ltd Loan Management System** is a **full-stack web application** developed using **Python, Django, and MySQL** that automates the complete loan management workflow digitally.

The system eliminates manual paperwork by providing a centralized platform for:
- Customer registration & authentication
- Loan application & approval processing
- EMI calculation & payment tracking
- PDF receipt & loan closure certificate generation
- Admin analytics dashboard

Developed as part of a **Software Development Internship** to gain practical exposure in full-stack web development, database management, and real-world application design.

---

## 🧩 Technology Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,mysql,html,css,js,git,github&theme=light" />
</p>

| Layer | Technology | Purpose |
|-------|-----------|---------|
| Backend | Django (Python) | MVT architecture, ORM, session management |
| Database | MySQL | Relational data storage & management |
| Frontend | HTML5, CSS3, JavaScript | Responsive UI & client-side logic |
| PDF Generation | ReportLab | EMI receipts & loan closure certificates |
| Analytics | Chart.js | Dashboard graphs & loan statistics |
| Version Control | GitHub | Source code management |

---

## 📦 Modules & Features

### 👤 User Module
- ✔️ Registration with personal, address, bank & employment details
- ✔️ Secure login & session management
- ✔️ Online loan application submission
- ✔️ Real-time loan status tracking
- ✔️ EMI calculation using standard formulas
- ✔️ EMI payment management & history
- ✔️ Downloadable PDF payment receipts
- ✔️ Loan closure certificate generation

### 🛠️ Admin Module
- ✔️ Review & approve / reject loan applications
- ✔️ Monitor customer records & transactions
- ✔️ EMI repayment tracking & management
- ✔️ Analytics dashboard with Chart.js visualizations
- ✔️ Centralized loan data management

---

## 🏗️ System Architecture

The application follows Django's **MVT (Model-View-Template)** architecture, ensuring clean separation of concerns between frontend, backend, and database layers.
## 📁 Project Structure
```
loan-project/
├── loan_project/          # Root Django project & settings
├── loan_app/              # Core application module
│   ├── models.py          # Database schema definitions
│   ├── views.py           # Business logic & request handling
│   ├── urls.py            # URL routing & navigation
│   └── forms.py           # Form handling & validation
├── templates/             # HTML templates (user & admin)
├── static/                # CSS, JavaScript & assets
├── media/                 # Uploaded documents & images
├── manage.py              # Django project manager
└── requirements.txt       # Project dependencies
```
---

## 🗄️ Database Design

The system uses **MySQL** with Django ORM for efficient CRUD operations.

**Core Tables:**

| Table | Description |
|-------|-------------|
| `AccountHolder` | Stores customer registration details |
| `LoanApplication` | Manages loan requests & details |
| `LoanApproval` | Tracks admin approval/rejection status |
| `Payment` | Records EMI payments & transactions |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Deepika6689/loan-project.git
cd loan-project
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Configure Database
Update `settings.py` with your MySQL credentials:
```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'your_db_name',
        'USER': 'your_username',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

### 4️⃣ Run Migrations
```bash
python manage.py migrate
```

### 5️⃣ Start the Server
```bash
python manage.py runserver
```

Local server at:
```
http://127.0.0.1:8000/
```
---

## 🔁 Application Flow
```
User Registration
       ↓
     Login
       ↓
Apply for Loan
       ↓
Admin Reviews Application
       ↓
  ┌────┴────┐
Approved  Rejected
  ↓
EMI Calculation
       ↓
EMI Payment
       ↓
PDF Receipt Generated
       ↓
Loan Closure Certificate
```
---

## 👩‍💻 Author

Hi there! <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px">

Made with ❤️ by **Deepika Sajjan**

<a href="https://www.linkedin.com/in/deepika-sajjan-22a041284/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="https://github.com/Deepika6689">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="mailto:deepikasajjan6689@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
