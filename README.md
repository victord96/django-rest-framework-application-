# Django REST API Project

This project is a Django application that uses the Django Rest Framework (DRF) to create a REST API.

## Features

- Provides a view called TestView that handles GET and POST requests to the '/' route
- Uses the IsAuthenticated permission class to ensure that only authenticated users can access the view
- Uses the StudentSerializer serializer to convert Student model objects into JSON format and vice versa
- Student model has fields for the name, age, description, and enrollment date of a student
- Provides a '/api/token/' route that is responsible for providing authentication tokens for users of the API

## Requirements

- Python 3.7 or higher
- Django 3.1 or higher
- Django Rest Framework 3.11 or higher

## Setup

1. Clone this repository

```git clone https://github.com/your-username/django-rest-api.git```

2. Change into the project directory

```cd django-rest-api```

3. Create a virtual environment and activate it

```python3 -m venv env```
```source env/bin/activate```

4. Install the required dependencies

```pip install -r requirements.txt```


5. Run the Django migrations

```python manage.py migrate```


6. Run the Django development server

```python manage.py runserver```

7. Open a web browser and go to http://localhost:8000 to access the API.