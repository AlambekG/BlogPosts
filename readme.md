# Blog App

A simple blog application built with Django.  
Users can create, edit, and publish blog posts.

## Features

- List of published posts
- Post detail view
- Admin interface for managing content

## Tech Stack

- Python 3
- Django 5
- SQLite

## Running Locally

```bash
git clone https://github.com/yourusername/blog-app.git
cd blog-app
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
