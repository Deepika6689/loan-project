# EasyLoan Finance Pvt Ltd — Loan Management System

## Overview

The **EasyLoan Finance Pvt Ltd Loan Management System** is a full-stack web application built with **Python, Django, and MySQL** that digitizes and automates the end-to-end loan management workflow.

The platform replaces manual, paper-based processes with a centralized system that handles:

- Customer registration and authentication
- Loan application submission and approval processing
- EMI (Equated Monthly Installment) calculation and payment tracking
- PDF receipt and loan closure certificate generation
- Administrative analytics and reporting

This project was developed as part of a Software Development Internship, with a focus on practical experience in full-stack web development, relational database design, and real-world application architecture.

---

## Technology Stack

| Layer | Technology | Purpose |
|---|---|---|
| Backend | Django (Python) | MVT architecture, ORM, session management |
| Database | MySQL | Relational data storage and management |
| Frontend | HTML5, CSS3, JavaScript | Responsive UI and client-side logic |
| PDF Generation | ReportLab | EMI receipts and loan closure certificates |
| Analytics | Chart.js | Dashboard visualizations and loan statistics |
| Version Control | Git / GitHub | Source code management |

---

## Features

### User Module

- Registration capturing personal, address, banking, and employment details
- Secure login and session management
- Online loan application submission
- Real-time loan status tracking
- EMI calculation using standard amortization formulas
- EMI payment management and transaction history
- Downloadable PDF payment receipts
- Loan closure certificate generation

### Admin Module

- Review and approval/rejection of loan applications
- Monitoring of customer records and transactions
- EMI repayment tracking and management
- Analytics dashboard with Chart.js visualizations
- Centralized management of loan data

---

## System Architecture

The application follows Django's **Model-View-Template (MVT)** architecture, maintaining a clean separation of concerns between the frontend, backend, and database layers.

### Project Structure

```
loan-project/
├── loan_project/          # Root Django project & settings
├── loan_app/               # Core application module
│   ├── models.py           # Database schema definitions
│   ├── views.py             # Business logic & request handling
│   ├── urls.py               # URL routing & navigation
│   └── forms.py              # Form handling & validation
├── templates/               # HTML templates (user & admin)
├── static/                    # CSS, JavaScript & assets
├── media/                    # Uploaded documents & images
├── manage.py                 # Django project manager
└── requirements.txt          # Project dependencies
```

---

## Database Design

The system uses **MySQL** in conjunction with Django's ORM for efficient CRUD operations.

**Core Tables:**

| Table | Description |
|---|---|
| `AccountHolder` | Stores customer registration details |
| `LoanApplication` | Manages loan requests and associated details |
| `LoanApproval` | Tracks admin approval/rejection status |
| `Payment` | Records EMI payments and transactions |

---

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Deepika6689/loan-project.git
cd loan-project
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure the Database

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

### 4. Run Migrations

```bash
python manage.py migrate
```

### 5. Start the Development Server

```bash
python manage.py runserver
```

The application will be available at:

```
http://127.0.0.1:8000/
```

---

## Application Workflow

1. User registers an account
2. User logs in
3. User submits a loan application
4. Admin reviews the application
5. Application is either **approved** or **rejected**
6. If approved, EMI is calculated
7. User makes EMI payments
8. PDF payment receipt is generated
9. Upon full repayment, a loan closure certificate is issued

---

## Author

**Deepika Sajjan**

- LinkedIn: [linkedin.com/in/deepika-sajjan-22a041284](https://www.linkedin.com/in/deepika-sajjan-22a041284/)
- GitHub: [github.com/Deepika6689](https://github.com/Deepika6689)
- Email: [deepikasajjan6689@gmail.com](mailto:deepikasajjan6689@gmail.com)
