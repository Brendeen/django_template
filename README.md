# django_template
A simple template for Django projects with a custom user.

To use this template.

Set up VENV -

    python3.11 -m venv .venv
    source .venv/bin/activate
    
Basic setup -

    pip install -r requirments.txt
    python manage.py migrate
    python manage.py createsuperuser
    python manage.py runserver
