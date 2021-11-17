# YogaClassroom

A Django React Application 

# This application is made in such a way that you dont need to compile react files in `frontend`, because django directly looking for the main `templates/frontend/index.html` HTML file, and all the neccesary compiled javascript is pointing to this file.
So just directly run `python manage.py runserver` after installing neccesary modules.

## All the neccesary validations is happening in the backend of the application i.e `./YogaForm`.

## Entity-Relationship Diagram For YogaClasses
![E-R UCL](https://user-images.githubusercontent.com/41137189/142236305-6f978ae1-c0ca-49d4-8568-bcf8b1570de6.jpg)

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
