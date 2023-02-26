# Tickets

This project is a POC (Proof Of Concept) on Flask.

## Setup the project in dev mode

```shell
git clone https://github.com/billkurios/tickets.git
```

```shell
❯ cd tickets
❯ virtualenv py_env
❯ source py_env/bin/activate
```

## Setup .env file

Before using a *.env* file, make sure *python-dotenv* is install.
To make it, just do in your virutalenv environnement
```shell
pip install python-dotenv
```

Create a *.env file* and theses keys with the right values for you.
```.env
FLASK_ENV='developement'
FLASK_APP='.'
SECRET_KEY='MY_SECRET_KEY'
HOST='127.0.0.1'
PORT=3000
```

## To run in dev mode
```shell
flask --env-file=.env run --host=127.0.0.1 --port=3000
```