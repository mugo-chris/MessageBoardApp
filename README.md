# Message Board app
This is the app that I developed in my first stages of learning **django framework**. It's just a simple app for displaying the posts messages.
## Table of contents

-[Installation](#installation)
-[Configuration](#configuration)

## Installation
```python
python -m venv .env
.env\Scripts\Activate.ps1
python -m pip install django
python -m pip install black
django-admin startproject messageboard .
python manage.py startapp message
```
## Configuration
Register the app message and every other third party packages installed in the `settings.py` file.
