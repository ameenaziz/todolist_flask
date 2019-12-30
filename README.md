## TODO app with Python and Flask

### Install and run irtual environment

`pip3 install virtualenv`
`pip3 install flask flask-sqlalchemy`
`virtualenv env`
`source env/bin/activate`

### Initailize database

python3 shell
`from app import db`
`db.create_all()`
