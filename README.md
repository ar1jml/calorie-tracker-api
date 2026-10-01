Calorie Tracker API

A RESTful calorie tracking API built with Django REST Framework and PostgreSQL.

Overview

Calorie Tracker API allows users to manage their nutrition data, track food consumption, and calculate daily calorie and nutrition totals.

The project is being built with a focus on clean backend architecture, REST API development, database design, testing, CI/CD, and production deployment.

Tech Stack

Python

Django

Django REST Framework

PostgreSQL

REST API

Git & GitHub

GitHub Actions

Render

Features

User authentication

User profile and nutrition goals

Food management

Food logging

Daily calorie tracking

Nutrition calculations

REST API endpoints

Automated testing

Continuous Integration

Production deployment

API
Health Check
GET /api/health/


Response:

{
    "status": "ok",
    "message": "Calorie Tracker API is running"
}

Project Structure
calorie-tracker-api/
├── config/
├── tracker/
├── .github/
│   └── workflows/
│       └── ci.yml
├── manage.py
├── requirements.txt
└── README.md

Development

Clone the repository:

git clone git@github.com:ar1jml/calorie-tracker-api.git
cd calorie-tracker-api


Create and activate a virtual environment:

python -m venv venv


Install dependencies:

pip install -r requirements.txt


Run migrations:

python manage.py migrate


Start the development server:

python manage.py runserver


The API will be available at:

http://127.0.0.1:8000/

Testing

Run the test suite with:

python manage.py test


GitHub Actions automatically runs the tests whenever changes are pushed to the repository.

Deployment

The project is prepared for production deployment with PostgreSQL and Render.

Status

Currently under active development.