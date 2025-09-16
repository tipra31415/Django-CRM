**Django CRM**


A simple Customer Relationship Management (CRM) system built with Django. This application allows users to manage customer records with full CRUD operations, user authentication, and a clean interface.
Features

User Authentication: Login, logout, and registration functionality
Customer Management: Add, view, edit, and delete customer records
Responsive Design: Bootstrap-powered UI for mobile and desktop
Secure Access: Protected routes requiring user authentication
User-Friendly Messages: Success and error notifications for all actions


**Tech Stack**

Backend: Django 5.2.6

Frontend: HTML5, CSS3, Bootstrap

Database: MYSQL

Python: 3.13.3

**Quick Start**
Follow these steps to get the project running locally:
1. Clone the Repository
```bash
git clone https://github.com/username/repo.git
cd repo
```
2. Create Virtual Environment
```bash
 python -m venv venv
```
3. Activate Virtual Environment
Windows (PowerShell/CMD):
```bash
 venv\Scripts\activate
```
Windows (Git Bash):
```bash
 source venv/Scripts/activate
```
macOS/Linux:
```bash
 source venv/bin/activate
```
4. Install Dependencies
```bash
 pip install django
```
5. Navigate to Project Directory
```bash
 cd dcrm
```
6. Setup Database
```bash
 python manage.py makemigrations
 python manage.py migrate
```
7. Create Admin User (Optional)
```bash
python manage.py createsuperuser
```
8. Run Development Server
```bash
python manage.py runserver
```
9. Access the Application
Open your web browser and go to:
http://127.0.0.1:8000/
