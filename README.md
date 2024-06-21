# django-ecs
Deploying a Django app to AWS ECS Fargate via Pulumi

# Install Dependencies
1. `brew install pulumi pyenv`
1. `pyenv install 3.9 && pyenv local 3.9`
1. `cd app`
1. `python -m venv venv`
1. `source venv/bin/activate`
1. `(venv)$ pip install -r requirements.txt`
1. `(venv)$ python manage.py migrate`

# Run Django app locally
1. `(venv)$ python manage.py runserver`
1. Nagivate to http://localhost:8000
