1. Login to Postgresql
```
sudo -u postgres psql
```
2. Create User
```
CREATE USER user_name WITH ENCRYPTED PASSWORD 'password';
```

3. Create Database
```
CREATE DATABASE database_name;
```

4. Drop Database
```
SELECT pg_terminate_backend(pg_stat_activity.pid) FROM pg_stat_activity WHERE pg_stat_activity.datname = 'db_name' AND pid <> pg_backend_pid();
DROP DATABASE database_name;
```

5. Grant Permission
```
GRANT ALL PRIVILEGES ON DATABASE database_name TO user_name;
```

6. Show Database
```
\l
```

7. import database
```
psql -U username dbname < file_name
```
```
psql -U username -h host_name -f database_file.sql -d database_name
```

8. export database
```
pg_dump -U username dbname > dbexport.pgsql
```
