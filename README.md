## Simple CRUD App

Simple CRUD Djangorestframework

### Test Case Scenarios
* Tes to verify registration.
* Tested authenticated user authorization with JWT.
* Create a todo with API.
* Update a todo with API.
* Update a todo with API.
* Delete a todo with API.

### API Docs Endpoints

* **/docs**


#### Todos

* **/api/todos/** (Todo create and list endpoint)
* **/api/todos/{todo-id}/** (Todo retrieve, update and destroy endpoint)

### Install 

    pip install -r requirements.txt

### Usage

    python manage.py runserver

### Notes

* required mysql server
* import db_sqldump.sql to your mysql database
* change database config in settings.py
* tested on windows 7

