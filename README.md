How To Run
Install virtualenv:
$ pip install virtualenv
Open a terminal in the project root directory and run:
$ virtualenv env
Then run the command:
$ .\env\Scripts\activate
Then install the dependencies:
$ (env) pip install -r requirements.txt
Finally start the web server:
$ (env) python app.py

My own notes:
(env) PS C:\Users\Julia\Documents\Year4\Project\Flask> python
>>> from app import db

# this should create database
>>> db.create_all()