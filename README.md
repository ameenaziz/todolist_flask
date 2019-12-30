## TODO app with Python and Flask

### Dependencies

`pip3 install virtualenv`</br>
`pip3 install flask flask-sqlalchemy`

### Virtual environment

`virtualenv env`</br>
`source env/bin/activate`

### Initialise database

````
```console
foo@bar:~$ python3

from app import db

db.create_all()

````
