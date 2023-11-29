Django React Tutorial

Commands Run
 
1.

 pip install django djangorestframework

 django-admin startproject music_controller

 cd .\music_controller\
 
 django-admin startapp api

#Initialize Django Database

 python .\manage.py makemigrations

 .\manage.py migrate 
 
 python .\manage.py runserver

/*
from django.urls import path -> imports function from a file
def main(request): -> to create functions in python
*/

/**Creating Table with Djando
  code = models.CharField(max_length = 8, default="", unique=True)
*/

/*
import string -> comes from Python standard library
*/

https://www.django-rest-framework.org/api-guide/generic-views/

From Tech With Tim