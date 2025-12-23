# Create Database

```sh
sudo apt update
sudo apt install postgresql postgresql-contrib -y
sudo service postgresql start
sudo service postgresql status
sudo -u postgres psql

ALTER USER postgres WITH PASSWORD 'root';
\q

sudo -u postgres createdb your-database
psql -U postgres -h localhost your-database
```

