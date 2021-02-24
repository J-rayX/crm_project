# Django REST API with PostgreSQL: A CRUD App

A Django RESTful API with PostgreSQL database for my tutorial: [Django Rest Framework with PostgreSQL: A CRUD Tutorial](https://jkaylight.medium.com/django-rest-framework-with-postgresql-a-crud-tutorial-8a34283e9c12).

### To Run on Localhost

- Have `Python` and `pip` installed on your local machine

### Running the Django project

Create an isolated environment for the project with `virtualenv`. You can install `virtualenv` with the following command:

```
sudo pip install virtualenv
```

Create a new directory for the project:

```
mkdir myproject && cd myproject
```

Create a virtual environment for the project:

```bash
virtualenv env
```

Then, activate it:

```bash
source env/bin/activate
```

Clone the project from GitHub:

```bash
git clone https://github.com/j-rayX/crm_project.git
```

Install Django and other packages:

```bash
pip install django djangorestframework psycopg2
```

Finally, `cd` into the _crm_project_ folder and run the project:

```bash
python manage.py runserver
```

**Spot on!**

Go to http://localhost:8000/customer/ to see if the API is up and running.
