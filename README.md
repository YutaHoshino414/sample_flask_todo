# flask-todo-app

Flask製Todoアプリ。

## Requirement

- Python 3.7.3

## Installation

```
$ git clone https://flask-todo-app-techdiary.herokuapp.com/
$ cd flask-todo-app/
$ pip install virtualenv
$ virtualenv -p python3.7.3 env
$ source env/bin/activate
$ pip install -r requirements.txt
```

## setting DB

```
$ python     (対話型シェル／インタラクティブモードを起動)
>>> from app import db
>>> db.create_all()
>>> exit()  *終了

$ python app.py
```