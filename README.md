# 🛒 Amarket

Amarket is a Django-based web application for managing an online marketplace. It features user authentication, product listings, chat between users, and dashboard analytics. The project is modular and follows Django best practices.

## 🚀 Features

- User registration and authentication
- Product (item) listings with images
- Chat system for user-to-user communication
- Dashboard for user management and item control
- Admin panel for backend management
- Media handling with Django
- Responsive templates using Tailwind CSS (or Bootstrap if applied)

## Project Structure
amarket/
│
├── amarket/ # Project configuration (settings, URLs, etc.)
├── core/ # Core app: user authentication, base templates
├── item/ # Item listing & management
├── chat/ # Chat system between users
├── dashboard/ # Admin dashboard for control and metrics
├── media/ # Uploaded files
├── manage.py # Django management script
└── requirements.txt# Python dependencies
└── requirements.txt# Python dependencies

yaml
Copy
Edit

## ⚙Installation & Setup
**Clone the repo**:
```
git clone https://github.com/ZeyadHassan41/amarket.git
cd amarket
Create a virtual environment:
```

## Deployment (PythonAnywhere)
Upload project to PythonAnywhere

Set up virtual environment and install requirements

Configure the WSGI file and static/media files

Add your domain to ALLOWED_HOSTS in settings.py

Reload the web app from the PythonAnywhere Web tab

##🧑‍💻 Author
Zeyad Hassan
GitHub | LinkedIn
