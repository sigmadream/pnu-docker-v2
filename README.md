# PNU-Docker-v2

## Image Build

```
$ docker build -t feedback-node .
$ docker run --rm -p 3000:80 feedback-node
$ docker run -p 3000:80 feedback-node
```

## Volume

```
$ docker volume ls
```

## with Volume

```
# Volumes
$ docker run --rm -p 3000:80 -v feedback:/app/feedback feedback-node

#
$ docker run --rm -p 3000:80 -v C:\Users\sigma\works\pnu\pnu-docker-v2:/app feedback-node
$ docker run --rm -p 3000:80 -v c:\Users\sigma\works\pnu\pnu-docker-v2:/app -v /app/node_modules feedback-node
```
