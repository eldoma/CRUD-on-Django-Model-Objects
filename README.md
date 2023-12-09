## CRUD-on-Django-Model-Objects
# Runnable either on IBM Cloud or in VS Code Standalone, database using Postgres (Cloud or local standalone) 
- pip install --upgrade distro-info
- pip3 install --upgrade pip==23.2.1 replace with  python.exe -m pip install --upgrade pip==23.3.1 --user 
- pip install virtualenv
- pip install django
- virtualenv djangoenv replace with  python -m venv djangoenv
- source djangoenv/bin/activate replace with .\djangoenv\Scripts\activate
- pip install Django psycopg2-binary

# then go to 
cd/project/lab2_template

- python3 manage.py makemigrations crud replace with python manage.py makemigrations crud 

- python3 manage.py migrate replace with python manage.py migrate

# then the Postgres should minimal be able to showing this:
- IBM Cloud
![Postgres_IBM](https://github.com/eldoma/CRUD-on-Django-Model-Objects/blob/main/CRUD%20in%20Postgres%20IBM%20Cloud.jpg)  
- Local VS Code Standalone
![Postgres_Local](https://github.com/eldoma/CRUD-on-Django-Model-Objects/blob/main/CRUD%20in%20Postgres.jpg)
