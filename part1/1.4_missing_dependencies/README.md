# 1.4 Missing Dependencies

## Start process

```
docker run -it ubuntu sh -c 'while true; do echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website; done'
```

## Commands to fix problems

```
docker exec -it intelligent_ramanujan bash
apt-get update
apt-get install -y curl
```

## Command to test fix

```
docker attach intelligent_ramanujan
```

