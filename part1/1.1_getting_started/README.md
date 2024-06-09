# 1.1 Getting Started

## Start 3 containers

```
docker run -d nginx
docker run -d httpd
docker run -d httpd
```

## Stop 2 containers

```
docker stop c0 53
```

## docker ps -a output

```
CONTAINER ID   IMAGE     COMMAND                  CREATED          STATUS                     PORTS     NAMES
53e0cb640c97   httpd     "httpd-foreground"       17 seconds ago   Exited (0) 4 seconds ago             serene_bhaskara
c0d9d8b1aa94   httpd     "httpd-foreground"       21 seconds ago   Exited (0) 4 seconds ago             vigorous_vaughan
1bf57347ad84   nginx     "/docker-entrypoint.…"   25 seconds ago   Up 25 seconds              80/tcp    laughing_rubin
```

