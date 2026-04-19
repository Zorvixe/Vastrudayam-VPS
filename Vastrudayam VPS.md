```bash
CREATE USER vastrudayamuser WITH ENCRYPTED PASSWORD 'vastrudayampassword';
```

```bash
CREATE DATABASE vastrudayamdb OWNER vastrudayamuser;
```

```bash
postgresql://vastrudayamuser:vastrudayampassword@127.0.0.1:5432/vastrudayamdb
```

```bash
 sudo nano /etc/nginx/sites-available/vastrudayam.com
```

```bash
sudo  nano /etc/nginx/sites-available/admin.vastrudayam.com
```

```bash
sudo nano /etc/nginx/sites-available/api.vastrudayam.com
```

```bash
certbot --nginx -d vastrudayam.com -d www.vastrudayam.com -d admin.vastrudayam.com -d api.vastrudayam.com
```
