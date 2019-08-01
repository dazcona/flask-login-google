# Flask Login with Google Boilerplate

Flask Login with Google Login Boilerplate to have a ready web app with user authentication provided by Google.

## Technologies

* [Flask](http://flask.pocoo.org/)
* [Flask-Login](https://flask-login.readthedocs.io/en/latest/)
* [Bootstrap](https://getbootstrap.com/)
* [requests](https://2.python-requests.org/en/master/)
* [oauthlib](https://oauthlib.readthedocs.io/en/v3.0.2/)
* [pyopenssl](https://www.pyopenssl.org/en/stable/)

## Deployment

### Virtual Environment using Bash

1. Creation of a virtual environments done by executing the command venv
2. Command to activate virtual environment
3. Install dependencies
4. List the libraries installed on your environment
5. Do your work!
6. When you are done, the command to deactivate virtual environment
```
$ python3 -m venv env/
$ source env/bin/activate
(env) $ pip install -r requirements.txt
(env) $ touch src/config.py
(env) $ python src/app.py
Initialized the database
(env) $ python src/app.py
Access via the web to https://127.0.0.1:5000/
(env) $ deactivate
```

## Resources

* https://github.com/realpython/materials/tree/master/flask-google-login
* Google Identity Platform: https://developers.google.com/identity/choose-auth
* https://github.com/neoighodaro/pusher-python-realtime-dashboard