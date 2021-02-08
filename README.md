Podman IN Docker images
=======================

Pind is a set of containerfiles for running podman using a Docker container.

Fedora
------

```
$ docker build -t pind-fedora - < Dockerfile.fedora
$ docker run -t --privileged --rm pind-fedora podman ps
```

CentOS
------

```
$ docker build -t pind-centos - < Dockerfile.centos
$ docker run -t --privileged --rm pind-centos podman ps
```

