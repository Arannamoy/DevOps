# 1. Docker

#### Check docker version
```bash
docker --version
```

#### Create a docker container
```bash
docker run -it --name Ubuntu -p 2022:22 -v /home/:/root ubuntu
```
#### Start docker container
```bash
docker start Ubuntu
```

#### Enter cmd of a docker container
```bash
docker exec -it Ubuntu bash
``` 

#### Log checking

```bash
docker logs container_name
```

#### List of image

```bash
docker images
```

#### List of container

```bash
docker -ps -a
```

#### Registry, Repository, Tag, Image, Container

#### Podman pod vs Docker container: 

|Podman pod|Docker container|
|-----------|----------------|
| group of container |  single container|
| used for testing env like Kubernetes (K8s) | For application running|