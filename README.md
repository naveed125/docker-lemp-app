# What is this
A simple Linux, Nginx, MySQL and PHP (LEMP) app that can be used to setup a new development environment.

# How to use
https://medium.com/@naveed125/how-to-install-linux-nginx-mysql-php-lemp-stack-in-under-10-minutes-using-docker-1f23bf0a3ee9

# Quick Setup
Thanks to [@rohit20001221](https://github.com/rohit20001221)
```
% ./setup.sh
Pulling db  ... done
Pulling web ... done

% ./start.sh
Creating network "lemp_default" with the default driver
Creating lemp_db_1 ... done
Creating lemp_web_1 ... done

% curl -i localhost
HTTP/1.1 200 OK
Server: nginx
Date: Fri, 29 Jan 2021 17:24:34 GMT
Content-Type: text/html; charset=UTF-8
Transfer-Encoding: chunked
Connection: keep-alive
X-Powered-By: PHP/7.2.10

OK - Fri, 29 Jan 21 17:24:34 +0000

% ./stop.sh
Stopping lemp_web_1 ... done
Stopping lemp_db_1  ... done
Removing lemp_web_1 ... done
Removing lemp_db_1  ... done
Removing network lemp_default
```
