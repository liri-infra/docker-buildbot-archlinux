# Continous integration worker for ArchLinux

This is a Docker container that acts as a CI worker
to build Liri packages for ArchLinux.

To build:

```sh
make build
```

Tag the container and push to the hub:

```sh
make push
```
