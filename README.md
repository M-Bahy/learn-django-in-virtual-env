# learn-django
install django in a virtual environment
```bash
pipenv install django
```
switch to the virtual environment terminal
```bash
pipenv shell
```
create a django project in the current directory
```bash
django-admin startproject project_name .
```
run the server (taking into account the settings in the settings.py file)
```bash
python manage.py runserver
```
By default, the server runs on port 8000. To change the port, specify it in the command
```bash
python manage.py runserver 8080
```
get the path of the python interpreter in the virtual environment
```bash
pipenv --venv
```
