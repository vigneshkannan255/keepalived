## Keepalived

### Install keepalived.
```
apt install keepalived
```
### Start and enable keepalived service.

```
systemctl start keepalived
systemctl enable keepalived
```

### configuration file path.

```
cat /etc/keepalived/keepalived.conf
nano /etc/keepalived/keepalived.conf
```
### Architecture - keepalived
![keepalived1](https://github.com/vigneshkannan255/keepalived/assets/32855922/fa4a9ed5-ce35-4e3a-95b6-a15cdd153fac)


### Keepalived with Nginx upstream.
### Install nginx.
```
apt install nginx
```
### Start and enable nginx service.

```
systemctl start nginx
systemctl enable nginx
```
### configuration file path.

```
cat /etc/nginx/sites-available/default
nano /etc/nginx/sites-available/default
```


### Architecture - keepalived and nginx upstream
![keepalived and nginx](https://github.com/vigneshkannan255/keepalived/assets/32855922/8bbd7f72-5297-4819-b758-a8ba7040f4d5)

