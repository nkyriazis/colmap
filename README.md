# Run COLMAP through docker

It takes some trickery to manage and display the X11 and the gl stuff through docker. To use this, do

## Host

```bash
# disable access control
xhost +
```

## Container

```bash
docker-compose run app
```

