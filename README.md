# Lab 6 – Introduction to Flask and Django Web Frameworks

## Overview
This lab demonstrates the implementation of two popular Python web frameworks: **Flask** and **Django**.  
The project showcases routing, templating, form handling, and database-driven content using Django models and the admin interface.

---

# Part 1 – Flask Application

## Implemented Features
- Home route (`/`) displaying: *"Welcome to Flask!"*
- Dynamic route (`/hello/<name>`) displaying personalized greeting
- Form page (`/form`) where user enters name
- Form submission redirects to dynamic greeting page
- Jinja2 template rendering (`hello.html`, `form.html`)

---

## How to Run Flask

1. Navigate to the `flask_app` directory  
2. Create a virtual environment  
3. Activate the virtual environment  
4. Install dependencies  
5. Run the application  
6. Open in browser:  
   `http://127.0.0.1:5000/form`

---

# Part 2 – Django Application

## Implemented Features
- Created `Message` model
- Integrated Django Admin panel
- Added 3 message entries through admin
- Created `/messages/` route to display all messages
- Template rendering using Django templating engine

---

## How to Run Django

1. Navigate to the `django_app` directory  
2. Activate virtual environment  
3. Install dependencies  
4. Apply migrations  
5. Create superuser (if not already created)  
6. Run the server  

Access in browser:
- Messages page: `http://127.0.0.1:8000/messages/`
- Admin panel: `http://127.0.0.1:8000/admin/`

---

## Technologies Used
- Python  
- Flask  
- Django  
- HTML Templates  
- SQLite (Django default database)

---
