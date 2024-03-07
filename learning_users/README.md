Python 3.12.0
pip 23.3.1

# create virtual environment
python -m venv envname
# activate virtual env
MyDjangoEnv\Scripts\activate
.MyDjangoEnv\Scripts\activate

# for local server
cd learing_users

# runserver
python manage.py runserver

# for migration
python manage.py makemigration
python manage.py migrate


# for superuser
python manage.py createsuperuser


