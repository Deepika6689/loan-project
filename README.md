# 💰 Loan Management System

## 🌟 About the Project
**Loan Management System** is a full-stack web application built using **Django** and **MySQL**. It provides a complete platform for managing loan applications, approvals, EMI payments, and financial analytics with separate interfaces for users and administrators.

---

## 🚀 Live Application
<p align="center">
  <a href="https://github.com/Deepika6689/loan-project">
    <img src="https://img.shields.io/badge/Visit-Repository-22c55e?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## 🧩 Technology Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,mysql,html,css,js&theme=light" />
</p>

---

## 📁 Project Structure
```
root/
│── loan_app/              # Core app - models, views, URLs
│   │── migrations/        # Database migration files
│   │── models.py          # Database models
│   │── views.py           # Business logic & controllers
│   │── urls.py            # App-level URL routing
│   └── admin.py           # Admin panel configuration
│── loan_project/          # Project configuration
│   │── settings.py        # Django settings
│   │── urls.py            # Root URL configuration
│   │── wsgi.py            # WSGI entry point
│   └── asgi.py            # ASGI entry point
│── templates/             # HTML templates
│   │── home.html          # Landing page
│   │── dashboard.html     # User dashboard
│   │── admin_dashboard.html  # Admin panel
│   │── apply_loan.html    # Loan application form
│   │── emi_payment.html   # EMI payment interface
│   │── loan_analytics.html   # Analytics dashboard
│   └── ...                # Other templates
│── media/                 # Uploaded files
│── manage.py              # Django management CLI
│── .env                   # Environment variables (not tracked)
└── README.md              # Project documentation
```
---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Deepika6689/loan-project.git
cd loan-project
```

### 2️⃣ Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install django mysqlclient python-decouple
```

### 4️⃣ Configure Environment Variables
Create a `.env` file in the root directory:

SECRET_KEY=your-secret-key-here
DB_PASSWORD=your-mysql-password

### 5️⃣ Setup MySQL Database
```sql
CREATE DATABASE loan;
```

### 6️⃣ Run Migrations
```bash
python manage.py migrate
```

### 7️⃣ Start the Server
```bash
python manage.py runserver
```

### 8️⃣ Open in Browser
http://127.0.0.1:8000/

---

## 🧪 How It Works
- Register or log in as a user or admin
- Users can **apply for loans** and track their status
- Admins can **approve or reject** loan applications
- Users can make **EMI payments** and view payment history
- Use the built-in **EMI calculator** to plan repayments
- Admins can view **loan analytics** and financial insights

---

## 🔮 Future Roadmap
▢ Email notifications for loan status updates
▢ PDF generation for loan statements
▢ OTP-based login for enhanced security
▢ Mobile responsive design improvements
▢ REST API support
▢ Loan repayment forecasting charts

---

## 🎯 Try It Yourself
1. Clone the repo and set up the virtual environment.
2. Configure your `.env` file with database credentials.
3. Run migrations and start the development server.
4. Register as a user and apply for a loan.
5. Log in as admin to approve loans and view analytics.

---

## 👩‍💻 Author
**Deepika**  
Continuous learning • Full Stack Explorer • Django + AI Enthusiast

