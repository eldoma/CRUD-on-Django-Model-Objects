## CRUD-on-Django-Model-Objects
# either IBM Cloud or in VS Code, database using Postgres 
- pip install --upgrade distro-info
- pip3 install --upgrade pip==23.2.1 replace with  python.exe -m pip install --upgrade pip==23.3.1 --user 
- pip install virtualenv
- pip install django
- virtualenv djangoenv replace with  python -m venv djangoenv
- source djangoenv/bin/activate replace with .\djangoenv\Scripts\activate
- pip install Django psycopg2-binary

#then go to 
cd/project/lab2_template

- python3 manage.py makemigrations crud replace with python manage.py makemigrations crud 

- python3 manage.py migrate replace with python manage.py migrate
