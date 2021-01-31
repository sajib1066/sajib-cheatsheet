1. Create Mysql Database
```
CREATE DATABASE database_name;
```

2. Delete/Drop Database
```
DROP DATABASE database_name;
```

3. Show Database
```
SHOW DATABASES;
```

4. Select Database
```
USE DATABASE database_name;
```

5. Create User
```
CREATE USER 'user_name'@'host_name' IDENTIFIED BY 'password';
```

6. Grant Access
```
GRANT type_of_permission PRIVILEGES ON database_name.table_name TO 'user_name'@'host_name';
FLUSH PRIVILEGES;
```

7. Revoke Permission
```
REVOKE type_of_permission ON database_name.table_name FROM 'user_name'@'host_name';
```
8. Login Database
```
mysql -u user_name -p
```

9. Remote Login
```
mysql -u user_name -p -h host_name
```
