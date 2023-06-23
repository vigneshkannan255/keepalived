<div align="center">
	<h1>
		<br>
    Keepalived
	</h1>
</div>



</div>

Keepalived provides frameworks for both load balancing and high availability. The load balancing framework relies on the well-known and widely used Linux Virtual Server (IPVS) kernel module, which provides Layer 4 load balancing. Keepalived implements a set of health checkers to dynamically and adaptively maintain and manage load balanced server pools according to their health. High availability is achieved by the Virtual Redundancy Routing Protocol (VRRP). VRRP is a fundamental brick for router failover. In addition, keepalived implements a set of hooks to the VRRP finite state machine providing low-level and high-speed protocol interactions. Each Keepalived framework can be used independently or together to provide resilient infrastructures.

</div>

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

