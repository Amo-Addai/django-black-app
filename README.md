# [Black Dashboard Django](#)
<!-- (https://django-black-app.AUTO.com/?ref=vbl-readme) -->

Full-stack platform, with a **Python - Django** Backend API, and a **Black UI** Frontend Dashboard app, a modern Bootstrap 5 design, and integrable with any SQL-Based database.


## Quick start

> 👉 Clone the repo  

```bash
$ git clone https://github.com/app-generator/django-black-app.git
$ cd django-black-app
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

> Note: To use the app, please access the registration page and create a new user. After authentication, the app will unlock the private pages.

<br />

> The bootstrap flow

- Django bootstrapper `manage.py` uses `core/settings.py` as the main configuration file
- `core/settings.py` loads the app magic from `.env` file
- Redirect the guest users to Login page
- Unlock the pages served by *app* node for authenticated users

<br />

