1. Login to Postgresql
```
sudo -u postgres psql
```

1. import database
```
psql -U username dbname < file_name
```
```
psql -U username -h host_name -f database_file.sql -d database_name
```
