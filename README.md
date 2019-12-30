## TODO app with Python and Flask

### Install and run virtual environment

`pip3 install virtualenv`
`pip3 install flask flask-sqlalchemy`

`virtualenv env`
`source env/bin/activate`

### Initialise database

````
```console
foo@bar:~$ python3

from app import db

db.create_all()

````
