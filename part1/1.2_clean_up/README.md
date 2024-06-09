# 1.2 Clean Up

## docker ps -a output

```
CONTAINER ID   IMAGE     COMMAND                  CREATED              STATUS                          PORTS     NAMES
53e0cb640c97   httpd     "httpd-foreground"       About a minute ago   Exited (0) About a minute ago             serene_bhaskara
c0d9d8b1aa94   httpd     "httpd-foreground"       About a minute ago   Exited (0) About a minute ago             vigorous_vaughan
1bf57347ad84   nginx     "/docker-entrypoint.…"   2 minutes ago        Up 2 minutes                    80/tcp    laughing_rubin
```

## docker image ls output

```
REPOSITORY   TAG       IMAGE ID       CREATED        SIZE
nginx        latest    705b7f60fea5   7 days ago     193MB
httpd        latest    251be5552bf4   2 months ago   177MB
```

## Commands to remove containers and images

```
docker stop 1b
docker container prune
docker rmi 70 25
```

## docker ps -a output

```
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
```

## docker image ls output

```
REPOSITORY   TAG       IMAGE ID   CREATED   SIZE
```
