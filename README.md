<h1 align="center">Django Portfolio</h1>

<p align="center"><b>My personal portfolio site built with Django, ready to deploy on Render or Railway.</b></p>

<p align="center">![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?logo=gunicorn&logoColor=white)</p>

## Overview

Personal portfolio website built with Django: home, about, skills, projects and contact sections; deploy-ready with Gunicorn, WhiteNoise and dj-database-url.

## Features

- Single-page sections: home, about, skills, projects, contact
- Production settings from environment variables (django-environ, dj-database-url)
- Static files via WhiteNoise; `Procfile` + `build.sh` for one-click deploys

## Tech stack

Python · Django · PostgreSQL · Gunicorn

## Getting started

```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver      # http://127.0.0.1:8000
```

## Project structure

`portifolio/` settings · `core/` app with `templates/sections`

---

<p align="center">Built by <a href="https://github.com/allan818181"><b>Allan Muganyizi Deus</b></a> · Full-Stack &amp; DevOps Engineer · Dar es Salaam, Tanzania<br/>
<a href="https://www.linkedin.com/in/allan-deus-4b888631a">LinkedIn</a> · <a href="mailto:allandeus014@gmail.com">Email</a></p>
