# Week-5-lab-hello-world
# Hello World Web App

This is a simple Django web app that returns a "Hello World!" message in JSON format.

## Requirements
- Python 3.x
- Django (install using `pip install django`)

## Installation
1. Clone the repository: `git clone <repository-url>`
2. Navigate to the project directory: `cd helloworld_project`
3. Create a virtual environment: `python -m venv myenv`
4. Activate the virtual environment: `source myenv/bin/activate` (or `myenv\Scripts\activate` on Windows)
5. Install dependencies: `pip install django`
6. Run migrations: `python manage.py makemigrations` and `python manage.py migrate`
7. Start the server: `python manage.py runserver`

## Access the Web App
- Open your web browser and go to: `http://127.0.0.1:8000/`

## Access the Hello World JSON Response
- Visit: `http://127.0.0.1:8000/hello/`

## Deactivate Virtual Environment
- When done, deactivate the virtual environment: `deactivate`
  
