# nginx-whoami

a simple http server of openresty in container, return it's hostname



## usage

```shell
$ docker run -d -p 8080:8080 dockersoap/nginx-whoami:latest
6fbadbd2597186a867381fdfe132c9b237273aea7bf4824b4e9c2ae0fb303c82


$ curl localhost:8080
I'm 6fbadbd25971
```