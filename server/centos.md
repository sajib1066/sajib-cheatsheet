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
