---
description: This page contains the details of the Django Project.
---

# Django Installation steps in windows

## 1. Installing Python3

```text
Download python 3 from the url(www.python.org)
```

## 2. Ensure pip3

```text
a) Add python 3 to PATH
b) pip checkbox is selected
c) Install for all users
```

## 3. Powershell Setup for execution of scripts

```text
Set-ExecutionPolicy Unrestricted
```

## 4. Check python version in powershell

```text
python -V
```

## 5. Install virtual environment

```text
pip install virtualenv
```

## 6. Create a folder structure

```text
C: or D: SampleProject and cd C:\SampleProject
```

## 7. Create a Virtualenv

```text
python -m venv venv
```

## 8. Activate the Virtual Environment

```text
.\Scripts\activate
```

## 6. Install Django in the virtual environment

```text
pip install django
```

## 7. Create a project

```text
django-admin.exe startproject djangoproject
```

## 8. Rename the project folder\(djangoproject\) to src

```text
mv djangoproject src/
```

## 9. Migrate Django default tables to the database and create superuser account

```text
cd src/
python manage.py migrate
python manage.py createsuperuser
```

## 10. Run development Server

```text
python manage.py runserver
```

## 11. Open the url in browser \(preferably in chrome\)

```text
http://localhost:8000
```



