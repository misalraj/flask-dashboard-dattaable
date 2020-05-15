# [Flask Dashboard DattaAble](https://appseed.us/admin-dashboards/flask-dashboard-dattaable)

> **Open-Source Admin Dashboard** coded in **Flask Framework** by **AppSeed** [Web App Generator](https://appseed.us/app-generator) - Features:

- UI Kit: **Datta Able Dashboard** (Lite Version) provided by **CodedThemes**
- SQLite, PostgreSQL, SQLAlchemy ORM
- Alembic (DB schema migrations)
- Modular design with **Blueprints**
- Session-Based authentication (via **flask_login**)
- Forms validation
- Deployment scripts: Docker, Gunicorn / Nginx
- **MIT License**
- Free support via **Github** 
- Paid Support **24/7 LIVE Support** via [Discord](https://discord.gg/fZC6hup)

> Links

- [Flask Dashboard Datta Able](https://appseed.us/admin-dashboards/flask-dashboard-dattaable) - Product page
- [Flask Dashboard Datta Able](https://flask-dashboard-dattaable.appseed.us/login) - LIVE demo
- More [Flask Admin Dashboards](https://appseed.us/admin-dashboards/flask) - index hosted by **AppSeed**
- [Free Admin Dashboards](https://appseed.us/admin-dashboards/open-source) - index hosted by **AppSeed**

<br />

## Want more? Go PRO!

PRO versions include **Premium UI Kits**, Lifetime updates and **24/7 LIVE Support** (via [Discord](https://discord.gg/fZC6hup))

| [Flask DattaAble Dark PRO](https://appseed.us/admin-dashboards/flask-dashboard-dattaable-dark-pro) | [Flask Atlantis Dark PRO](https://appseed.us/admin-dashboards/flask-dashboard-atlantis-dark-pro) | [Flask StarAdmin Dark PRO](flask-dashboard-staradmin-black-pro) |
| --- | --- | --- |
| [![Flask DattaAble Dark PRO](https://raw.githubusercontent.com/app-generator/flask-dashboard-dattaable-dark-pro/master/media/flask-dashboard-dattaable-dark-pro-screen.png)](https://appseed.us/admin-dashboards/flask-dashboard-dattaable-dark-pro) | [![Flask Atlantis Dark PRO](https://raw.githubusercontent.com/app-generator/flask-dashboard-atlantis-dark-pro/master/media/flask-dashboard-atlantis-dark-pro-screen.png)](https://appseed.us/admin-dashboards/flask-dashboard-atlantis-dark-pro) | [![Flask StarAdmin Dark PRO](https://raw.githubusercontent.com/app-generator/flask-dashboard-staradmin-black-pro/master/media/flask-dashboard-staradmin-black-pro-screen.png)](https://appseed.us/admin-dashboards/flask-dashboard-staradmin-black-pro)

<br />
<br />

![Flask Dashboard Datta Able - Open-Source Dashboard.](https://raw.githubusercontent.com/app-generator/static/master/flask-dashboard-dattaable/flask-dashboard-dattaable-screen.png)

<br />

## How to use it

```bash
$ # Get the code
$ git clone https://github.com/app-generator/flask-dashboard-dattaable.git
$ cd flask-dashboard-dattaable
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ # Install modules - SQLite Database
$ pip3 install -r requirements.txt
$
$ # OR with PostgreSQL connector
$ # pip install -r requirements-pgsql.txt
$
$ # Set the FLASK_APP environment variable
$ (Unix/Mac) export FLASK_APP=run.py
$ (Windows) set FLASK_APP=run.py
$ (Powershell) $env:FLASK_APP = ".\run.py"
$
$ # Set up the DEBUG environment
$ # (Unix/Mac) export FLASK_ENV=development
$ # (Windows) set FLASK_ENV=development
$ # (Powershell) $env:FLASK_ENV = "development"
$
$ # Start the application (development mode)
$ # --host=0.0.0.0 - expose the app on all network interfaces (default 127.0.0.1)
$ # --port=5000    - specify the app port (default 5000)  
$ flask run --host=0.0.0.0 --port=5000
$
$ # Access the dashboard in browser: http://127.0.0.1:5000/
```

<br />

## Deployment

The app is provided with a basic configuration to be executed in [Docker](https://www.docker.com/), [Gunicorn](https://gunicorn.org/), and [Waitress](https://docs.pylonsproject.org/projects/waitress/en/stable/).

<br />

### [Docker](https://www.docker.com/) execution
---

The application can be easily executed in a docker container. The steps:

> Get the code

```bash
$ git clone https://github.com/app-generator/flask-dashboard-dattaable.git
$ cd flask-dashboard-dattaable
```

> Start the app in Docker

```bash
$ sudo docker-compose pull && sudo docker-compose build && sudo docker-compose up -d
```

Visit `http://localhost:5005` in your browser. The app should be up & running.

<br />

### [Gunicorn](https://gunicorn.org/)
---

Gunicorn 'Green Unicorn' is a Python WSGI HTTP Server for UNIX.

> Install using pip

```bash
$ pip install gunicorn
```
> Start the app using gunicorn binary

```bash
$ gunicorn --bind 0.0.0.0:8001 run:app
Serving on http://localhost:8001
```

Visit `http://localhost:8001` in your browser. The app should be up & running.


<br />

### [Waitress](https://docs.pylonsproject.org/projects/waitress/en/stable/)
---

Waitress (Gunicorn equivalent for Windows) is meant to be a production-quality pure-Python WSGI server with very acceptable performance. It has no dependencies except ones that live in the Python standard library.

> Install using pip

```bash
$ pip install waitress
```
> Start the app using [waitress-serve](https://docs.pylonsproject.org/projects/waitress/en/stable/runner.html)

```bash
$ waitress-serve --port=8001 run:app
Serving on http://localhost:8001
```

Visit `http://localhost:8001` in your browser. The app should be up & running.

<br />

## Credits & Links

### [Flask Admin Dashboards](https://appseed.us/admin-dashboards/flask)

Index with UI-ready **admin dashboards** generated by the AppSeed platform in [Django Framework](https://www.djangoproject.com/).
Start fast your next Django project by using functional admin dashboards enhanced with Database, ORM, authentication flow, helpers and deployment scripts.

<br />

### [What is Flask](https://docs.appseed.us/what-is/flask/)

[Flask](https://flask.palletsprojects.com/) is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as a simple wrapper around Werkzeug and Jinja and has become one of the most popular Python web application frameworks.

<br />

### [What is a dashboard](https://en.wikipedia.org/wiki/Dashboard_(business))

A dashboard is a set of pages that are easy to read and offer information to the user in real-time regarding his business. A dashboard usually consists of graphical representations of the current status and trends within an organization. Having a well-designed dashboard will give you the possibility to act and make informed decisions based on the data that your business provides - *definition provided by [Creative-Tim - Free Dashboard Templates](https://www.creative-tim.com/blog/web-design/free-dashboard-templates/?ref=appseed)*.

<br />

### [DattaAble Free Dashboard](https://codedthemes.com/item/datta-able-bootstrap-lite/)

Datta Able Bootstrap Lite is the most styled Bootstrap 4 Lite Admin Template, around all other Lite/Free admin templates in the market. It comes with high feature-rich pages and components with fully developer-centric code. Comes with error/bug-free, well structured, well-commented code and regularly with all latest updated code, which saves your large amount of developing backend application time and it is fully customizable. - provided by **CodedThemes**.

<br />

---
[Flask Dashboard Datta Able](https://appseed.us/admin-dashboards/flask-dashboard-dattaable) - Provided by **AppSeed** [Web App Generator](https://appseed.us/app-generator).
