# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from github.

### STEP 2:
Create a new app.

### STEP 3:
Enter the code for admin.py and models.py

## STEP 4:
Create django app and add student details.

## PROGRAM
```
from django.db import models

# Create your models here.
from django.db import models
from django.contrib import admin
# create your models here
class hangout(models.Model):
    visitorname = models.CharField(max_length=10,primary_key=True)
    visitorage = models.IntegerField()
    pickuplocation = models.CharField(max_length=50)
    venue = models.CharField(max_length=30)
    numberofperson = models.IntegerField()

class hangoutAdmin(admin.ModelAdmin):

    list_display = ('visitorname','visitorage','pickuplocation','venue','numberofperson')
Include your code here
```


## OUTPUT
![Screenshot 2023-05-11 144515](https://github.com/SudharsanamRK/django-orm-app/assets/115523484/e8dd044d-e518-48cf-aa1d-76cc5a1af514)

![Screenshot 2023-05-11 144440](https://github.com/SudharsanamRK/django-orm-app/assets/115523484/8e9d323e-c3ed-4ce0-bbdf-53e26df406a5)

## RESULT
Hence we've developed a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).
