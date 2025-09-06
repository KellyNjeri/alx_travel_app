# ALX Travel App

A Django-based travel listing platform.

## Features

- Django REST Framework for API development
- MySQL database integration
- Swagger API documentation
- CORS headers configuration
- Environment variable management with django-environ

## Setup

1. Clone the repository
2. Create a virtual environment: `python -m venv ve`
3. Activate the virtual environment: `.\ve\Scripts\Activate.ps1` (Windows PowerShell) or `source ve/bin/activate` (macOS/Linux)
4. Install dependencies: `pip install -r requirements.txt`
5. Create a `.env` file with your environment variables (use the provided .env.example as a template)
6. Run migrations: `python manage.py migrate`
7. Start the development server: `python manage.py runserver`

## API Documentation

Access Swagger UI at: http://localhost:8000/swagger/

## Project Structure

(Include your project structure here)
