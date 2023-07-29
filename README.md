# Environment Setup 

* Clone Repo
> `git clone git@github.com:marvincdelacruz/lighthousecuts.git` 
* Install brew (macOS)
> `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
* Install pyenv 
> macOS: `brew install pyenv-virtualenv`
* Install python 3.9.10 
> `pyenv install 3.9.101`
* Install Node @ nodejs.org
* Create, activate environment, and install backend requirements
> `pyenv virtualenv 3.9.10 <venv_name>`
> `pyenv activate <venv_name>`
> `pip install -r requirements.txt`

# Steps Taken to Setup Project 
* Make Separate Folders for Frontend and Backend
> `mkdir frontend` 
> `mkdir backend` 
* Initialize Django Project 
> `cd backend`
> `django-admin startproject lighthousecutsproject` Creates Django project files wsgi.py, urls.py, etc.
* Initialize Django App
> `cd lighthousecutsproject`
> `python manage.py startapp lighthousecutsapp`  Creates Django app directory and files models.py, views.py, etc.
* Setup and Initialize React Frontend 
> `npx create-react-app lighthousecutsapp` Initializes the frontend directory structure including template source code.

