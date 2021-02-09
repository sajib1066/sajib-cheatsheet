```
sudo yum install snapd
```

```
sudo systemctl enable --now snapd.socket
```

```
sudo ln -s /var/lib/snapd/snap /snap
```

```
sudo snap install core;
```

```
sudo snap refresh core
```

```
sudo snap install --classic certbot
```

```
sudo ln -s /snap/bin/certbot /usr/bin/certbot
```

```
sudo certbot --nginx
```
