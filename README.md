# Fastfoodfast-API
What does this PR do?
creates the required endpoints
Description of tasks to be completed
Endpoints
        - POST/place and order
        - GET/get order by id
        - GET/get all orders
        - DELETE / delete a specific order by Id
        - PUT / update the status of an order
How can this be manually tested?
clone the repo as below:

https://github.com/evans17/Fastfoodfast-API.git

Create a virtualenvironment and activate it

virtualenv env --python=python3.6
source .env
Install all the dependencies needed by

pip install -r requirements.txt

Run the flask application

export FLASK_APP = run.py
export MODE = development
flask run 

###Endpoints Postman Testing
open postman and enter all the required sections i.e name,price and descripition as show below

GET/orders _ Get all orders
GET/orders/<orderId> _ get  specific order
POST/orders _ place a new  order
PUT/orders/<orderId> _ update the status of an order

