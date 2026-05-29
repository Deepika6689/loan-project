# 💰 Loan Management System

## 🌟 About the Project
The **Loan Management System** is a full-stack web application developed using **Django** and **MySQL**. It provides a complete platform for managing loan applications, approvals, EMI payments, and financial analytics with separate interfaces for users and administrators.

The system streamlines the loan process by allowing users to apply for loans online, track application status, and manage repayments, while admins can approve or reject applications and monitor financial analytics efficiently.

---

## 🧩 Technology Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,mysql,html,css,js&theme=light" />
</p>

- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Django (Python)  
- **Database:** MySQL  
- **Environment Management:** python-decouple  
- **Version Control:** Git & GitHub  

---

## 📁 Project Structure

```bash
root/
│── loan_app/                  # Core application
│   │── migrations/            # Database migration files
│   │── models.py              # Database models
│   │── views.py               # Business logic
│   │── urls.py                # App routes
│   └── admin.py               # Admin configuration
│
│── loan_project/              # Project configuration
│   │── settings.py            # Django settings
│   │── urls.py                # Root URL routing
│   │── wsgi.py                # WSGI entry point
│   └── asgi.py                # ASGI entry point
│
│── templates/                 # HTML templates
│   │── home.html
│   │── dashboard.html
│   │── admin_dashboard.html
│   │── apply_loan.html
│   │── emi_payment.html
│   │── loan_analytics.html
│   └── ...
│
│── media/                     # Uploaded files
│── manage.py                  # Django management file
│── .env                       # Environment variables
└── README.md                  # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Deepika6689/loan-project.git
cd loan-project
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Activate the Virtual Environment

#### Windows
```bash
venv\Scripts\activate
```

#### macOS/Linux
```bash
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install django mysqlclient python-decouple
```

### 5️⃣ Configure Environment Variables

Create a `.env` file in the root directory and add:

```env
SECRET_KEY=your-secret-key-here
DB_PASSWORD=your-mysql-password
```

### 6️⃣ Setup MySQL Database

```sql
CREATE DATABASE loan;
```

### 7️⃣ Run Database Migrations

```bash
python manage.py migrate
```

### 8️⃣ Create Superuser (Admin)

```bash
python manage.py createsuperuser
```

### 9️⃣ Start the Development Server

```bash
python manage.py runserver
```

### 🔗 Open in Browser

```bash
http://127.0.0.1:8000/
```

---

## 🚀 Features

### 👤 User Features
- User registration and login
- Apply for loans online
- Track loan application status
- EMI payment management
- EMI calculator
- View repayment history

### 🛠️ Admin Features
- Approve or reject loan applications
- Manage users and loans
- Monitor EMI payments
- View loan analytics and financial reports
- Access admin dashboard

---

## 🧪 How It Works

1. Register or log in as a user  
2. Apply for a loan using the application form  
3. Admin reviews the application  
4. Loan gets approved or rejected  
5. Approved users can pay EMIs and track repayment history  
6. Admin can monitor analytics and manage the system  

---

## 🔮 Future Enhancements

- 📧 Email notifications for loan updates  
- 📄 PDF generation for loan statements  
- 🔐 OTP-based authentication  
- 📱 Improved mobile responsiveness  
- 🌐 REST API integration  
- 📊 Loan repayment forecasting charts  

---

## 🎯 Try It Yourself

1. Clone the repository  
2. Configure the `.env` file  
3. Run migrations  
4. Start the server  
5. Register as a user and apply for a loan  
6. Log in as admin to manage applications  

---

## 👩‍💻 Author

**Deepika**  
🎓 AIML Engineering Student  
💻 Django & Full Stack Enthusiast  
🚀 Passionate About AI and Web Development  

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub.
