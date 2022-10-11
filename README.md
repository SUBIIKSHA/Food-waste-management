# Food-waste-management

### It is a description of our food waste management system

## Table of Content

+ [Description](#description)
+ [Technology Used](#technology-used)
+ [Installation Requirement](#Installation)


## Description
<p>This is a website where those resturant that have got excess food can post the food online and those without food can log in the website to see the posted food and the location of the pickup point instead of throwing away the food </p>


## Technology used
This Project is created using:
* HTML
* CSS
* Python Django
* Tailwind



## Installation 
### Requirements
* Python3
#### Process
 **From the project directory:**
* Install requirements from requirements.txt
```
 $ pip install requirements.txt
```
* Run migrations for django default apps
```
$ python manage.py migrate
```
* Run the custom apps migrations
```
$ python manage.py makemigrations catalog UserAuth
$ python manage.py migrate
```
* Create a superuser administrator
```
$ python manage.py createsuperuser
```
* Run server
```
$ python manage.py runserver
```




