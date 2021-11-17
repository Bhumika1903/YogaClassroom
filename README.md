# YogaClassroom

A Django React Application 

# This application is made in such a way that you dont need to compile react files in `frontend`, because django directly looking for `templates/frontend/index.html` HTML file, and all the neccesary javascript is pointing to this file.
So just directly run `python manage.py runserver` after installing neccesary modules.

# Try It

https://flexmoney-yoga-form.herokuapp.com/

## Setup Instructions

### Create Virtual Environment and Install Required Python Modules
`cd YogaClassroom`

Install venv
`pip install virtualenv`

For Creating a venv run this 
`virtualenv -p python3 venv`

Activate virtualenv 
`venv\Scripts\activate`

Install requirements
```bash
pip install -r requirements.txt
```
### Start Web Server

To start the web server you need to run the following sequence of commands.

Run the django web server.
```bash
python manage.py runserver
```
### OPTIONAL

## [Install Node.js](https://nodejs.org/en/)

## Install Node Modules

First cd into the ```frontend``` folder.
```bash
cd frontend
```
Next install all dependicies.
```bash
npm i
```
