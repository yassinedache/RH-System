# RH-System
A complete HR Management System built with Django. Features include employee management, leave tracking, payroll, contracts, recruitment, performance evaluation, and dashboards. Ideal for automating and optimizing HR operations in any organization.

#  Human Resources Management System

A comprehensive Human Resources (HR) Management System developed using **Django**, designed to manage all aspects of human resource operations for a company or organization.

##  Features

-  **Employee Management**: Add, update, and organize employee profiles.
-  **Leave Management**: Track leave requests, approvals, and balances.
-  **Payroll & Salary Management**: Automate salary calculations, deductions, and payslips.
-  **Contract Management**: Manage employment contracts and renewal periods.
-  **Performance Evaluation**: Define KPIs and track performance reviews.
-  **Recruitment Module**: Manage job postings, applications, and hiring stages.
-  **Analytics & Dashboards**: Real-time statistics and HR insights.
-  **Favorites/Shortcuts**: Quick access to frequently used modules.

##  Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript (optionally with Bootstrap)
- **Database**: SQLite (default) or PostgreSQL/MySQL
- **Admin Panel**: Django Admin Interface

##  Installation

1. **Clone the repository:**
   
   git clone https://github.com/your-username/hr-management-system.git
   cd hr-management-system
   
2. **Create and activate a virtual environment:**
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   
3. **Install dependencies:**
   pip install -r requirements.txt

4. **Apply migrations:**
   python manage.py makemigrations
   python manage.py migrate

5. **Create a superuser:**
   python manage.py createsuperuser


6. **Run the development server:**
   python manage.py runserver
   Visit http://127.0.0.1:8000 in your browser.


  # Project Structure

  hr-management-system/
├── backend/ # Django backend
│ ├── api/ # Main API logic (views, models, serializers)
│ ├── core/ # Settings and core configuration
│ ├── manage.py # Django management script
│ └── requirements.txt # Python dependencies
│
├── frontend/ # React frontend
│ ├── src/
│ │ ├── components/ # UI Components (auth, dashboard, employees)
│ │ ├── services/ # API handling and utilities
│ │ ├── App.js # Main React component
│ │ └── index.js # Entry point
│ ├── package.json # Node dependencies
│ └── .env # Environment variables
│
└── README.md




   
