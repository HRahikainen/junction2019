# ayyHello! Backend

Backend is implemented in Python Flask framework. 

API features the following endpoints:

GET:
- / -> Hello World message
- /el -> Electricity consumption data (JSON)
- /heat -> Heat -||-
- /water -> Water -||-
- /dir -> Direction of hand (JSON)

POST:
- /dir -> Direction of hand {"direction" : "L" | "R" | "U"}


## Setup

1. Install Pipenv package to manage virtual environment ```sudo pip3 install pipenv```
2. Install requirements from Pipfile: ```pipenv shell``` and then ```pipenv install```
3. Run server on port 5000 with ```pipenv run python app.py```

Enjoy!
