# Process of login with JWT, Flask, SQLAlchemy

# Installation
```
pip3 install  flask
pip3 install flask_sqlalchemy
pip3 install  mysqlclient
pip3 install MySQLdb
pip3 install Flask-SQLAlchemy
pip3 install mysql-python
pop3 install jwt

```

# Usage
```
from flask import *
import datetime
from flask_sqlalchemy import SQLAlchemy
import pymysql
import jwt

```

# Examples
When viewing the index  page, it has two functions. 1. Is the login page, 2. Is a protected page. In the former case you need to enter the login and password, in the latter case you need to write the token. Then you will see the answer on this page
