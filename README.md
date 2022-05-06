# postgresql-pgadmin

Install postgresql
* $ sudo apt install postgresql

Set a password for postgresql:
* $ sudo -u postgres psql
 password = moradi :)

Connect to postgres shell:
* $ psql -U postgres -h localhost

list of tables for example:
postgres=# \l

list of roles:
postgres=# \du

Create a role:
postgres=# CREATE USER kari WITH CREATEDB LOGIN ENCRYPTED PASSWORD 'mari' ;

Create a database:
postgres=# CREATE DATABASE karidata ;

Grand privileges:
postgres=# GRANT ALL PRIVILEGES ON DATABASE karidata TO kari;

INSTALL pgAdmin on deb system:
pgAdmin 4 (APT)
https://www.pgadmin.org/download/pgadmin-4-apt/

The pgAdmin4 master password is "mgAdmin"

for the configuration:
$ sudo /usr/pgadmin4/bin/setup-web.sh 
