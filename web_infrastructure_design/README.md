# **Web infrastructure design**

# Tasks

## **0 - Simple web stack**
Used:
1 server
1 web server (Nginx)
1 application server
1 application files (your code base)
1 database (MySQL)
1 domain name foobar.com configured with a www record that points to your server IP 8.8.8.8
![Task_0](https://zupimages.net/up/23/44/zvbo.jpg)




## **1-distributed_web_infrastructure**
Added:
2 servers
1 web server (Nginx)
1 application server
1 load-balancer (HAproxy)
1 set of application files (your code base)
1 database (MySQL)
[Task_1](https://zupimages.net/up/23/44/g9cn.png)




## **2-secured_and_monitored_web_infrastructure**
Added:
3 firewalls
1 SSL certificate to serve www.foobar.com over HTTPS
3 monitoring clients (data collector for Sumologic or other monitoring services)
[Task_2](https://zupimages.net/up/23/44/srf4.jpg)




## **3-scale_up**
Added:
1 server
1 load-balancer (HAproxy) configured as cluster with the other one
Split components (web server, application server, database) with their own server
[Task_3](https://zupimages.net/up/23/44/xv9s.png)




* **Sabrina PAPEAU** - [Github](https://github.com/Holbiwan)
