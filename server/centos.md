1. Add User to Sudo User Group
```
usermod -aG wheel user_name
```
```
sudo whoami
```

2. Without Password access
```
sudo visudo
```
```
username ALL=(ALL) NOPASSWD:ALL
```

3. User Permissions
```
sudo chown -R username:username /opt/folder_name
```
```
sudo chmod -R g+ws /opt/folder_name
```
```
 sudo setfacl -Rdm u::rwx,g::rwx,o::r-x /opt/folder_name
```
```
sudo setfacl -Rdm u::rwx,g::rwx,o::r-x /opt/folder_name
```
```
sudo chown -R username:nginx /opt/folder_name
```
