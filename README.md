# Tutorial Steps
## Virtual environment for python
```
$ python3 -m vevn venv
$ source venv/bin/activate
```

## Install flask
```
$ pip install flask
```

## Database creation
```
$ mkdir tmp && touch tmp/flaskr.db
$ python
>>> from flaskr import init_db
>>> init_db()
```

## Run Server
- current host & port set by 0.0.0.0/5000 (anywhere port 5000)
```
$ python flaskr.py
```
