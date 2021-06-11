Podman IN Docker images
=======================

Pind is a set of containerfiles for running podman using a Docker container.

Fedora
------

```
$ docker build -t pind-fedora - < Dockerfile.fedora
$ docker run -it --privileged --rm pind-fedora podman ps
```


A pre-built image is available from:

```
$ docker pull quay.io/gbraad/pind:latest
```


CentOS
------

```
$ docker build -t pind-centos - < Dockerfile.centos
$ docker run -it --privileged --rm pind-centos podman ps
```

CentOS 8 Stream
---------------

```
$ docker build -t pind-centos-stream8 - < Dockerfile.centos-stream8
$ docker run -it --privileged --rm pind-centos-stream8 podman ps
```
