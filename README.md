# REST-API-with-Flask-Connexion

****

In this project I use Python3, Flask and [Connexion](/https://github.com/zalando/connexion) to build a REST APIs
that can include i/o validation. The project also provides [Swagger] (/https://swagger.io) documentation. In addition,
a web application is created that demonstrates using the API with Javascript. The REST API builds  and serves a simple 
people data structure.\\

The project consists of several steps.\\

1.  First, a web server using Flask is created. Then Connexion module is used to add a REST API endpoint. This in turn allows a Python program to use the Swagger specification. The latter provides a lot of functionality including validation of i/o data to and from API, a really nice UI interface among others. The file swagger.yml gets it done. The file people.py creates database manually, however, this will be changes in the next step. The next step is to display the people on a web application that allow CRUD. This is done by AJAX calls from JavaScript to the people API URL endpoints. Finally some static css and js files are added for a better web interface.\\

2.


\\
References:
https://realpython.com/flask-connexion-rest-api/
https://swagger.io

