# 🔐 Django JWT Authentication System

A secure and scalable JWT-based authentication system built with Django and Django REST Framework. This project provides modular endpoints for user registration, login, token management, and logout using JSON Web Tokens.

## 🚀 Features

- User registration and login
- JWT access and refresh tokens
- Token refresh and verification
- Logout with token blacklisting
- Customizable user model support
- Consistent API response format with `status` and `success` fields

## 🛠️ Tech Stack

- **Framework**: Django 4.x
- **API**: Django REST Framework
- **Auth**: djangorestframework-simplejwt
- **Language**: Python 3.10+
- **Database**: SQLite (default)

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/jwt-auth-django.git
cd jwt-auth-django

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run the server
python manage.py runserver
