# Linux server configuration project
Below are information helpful in grading the server configuration project

## server information
url: http://ec2-18-218-211-94.us-east-2.compute.amazonaws.com/
ip address: 18.218.211.94
ssh port: 22 and 2200
http port: 80
ntp port: 123

## user grader information
username grader

## Additional softwares downloaded from base ubuntu os
apache2
libapache2-mod-wsgi
python-pip

## global python packages needed to be downloaded using pip
flask
flask-httpauth
itsdangerous
google-api-python-client
google-auth
google-auth-httplib2
google-auth-oauthlib
sqlalchemy

### a complete list of the pip packages listed on server machine using ```pip list```
```
cachetools (2.0.1)
certifi (2018.1.18)
chardet (3.0.4)
click (6.7)
Flask (0.12.2)
Flask-HTTPAuth (3.2.3)
google-api-python-client (1.6.5)
google-auth (1.3.0)
google-auth-httplib2 (0.0.3)
google-auth-oauthlib (0.2.0)
httplib2 (0.10.3)
idna (2.6)
itsdangerous (0.24)
Jinja2 (2.10)
MarkupSafe (1.0)
oauth2client (4.1.2)
oauthlib (2.0.6)
pip (8.1.1)
pyasn1 (0.4.2)
pyasn1-modules (0.2.1)
requests (2.18.4)
requests-oauthlib (0.8.0)
rsa (3.4.2)
setuptools (20.7.0)
six (1.11.0)
SQLAlchemy (1.2.1)
uritemplate (3.0.0)
urllib3 (1.22)
Werkzeug (0.14.1)
wheel (0.29.0)
```

# psql
```
postgres=# CREATE USER catalog WITH PASSWORD 'catalog';
CREATE ROLE
postgres=# CREATE DATABASE catalog;
CREATE DATABASE
postgres=# GRANT ALL PRIVILEGES ON DATABASE catalog to catalog;
GRANT
postgres=# ALTER DATABASE catalog OWNER to catalog;
ALTER DATABASE
```