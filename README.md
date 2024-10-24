# ToDo App in Django
This is a To Do List App created using django with user authentication.

## Installation
we need to first create a virtual environment to run our django app.

```bash
python3 -m venv virtualenv
```

To activate virtual environment:
```bash
source virtualenv/bin/activate
```
After activating virtual environment, install required packages..
```bash
pip install -r requirements.txt
```

Spin up SQLite DB
```bash
python manage.py migrate
```
Now clone the repository inside the ```virtualenv``` folder.

To run the application:
```bash
python manage.py runserver
```
