# Feedback-App
Python web app that allows users to submit feedback. Built with Flask, Postgresql and mailtrap.io following Brad Traversy's wep app [tutorial](https://youtu.be/w25ea_I89iM)  
Deployed on Heroku: [Feedback-app](https://subarufeedback.herokuapp.com/).

## How to start
* Setup a virtual environment and install the requirements:
```
pip install -r requirements.txt
```
* Install [Postgresql](https://www.postgresql.org/download/) and [pgAdmin4](https://www.pgadmin.org/download/)
* Sign up on [mailtrap.io](https://mailtrap.io/) and get your login and password.
* Add environment variables such as DATABASE_URI, mailtrap login and password.  
```
python app.py
```