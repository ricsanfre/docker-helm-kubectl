# Debian Docker Image with  kubectl and helm

helm and kubectl binaries within a docker image supporting multiarchitecture AMD64 and ARM64.

### Usage
Pull docker image `docker pull ricsanfre/docker-kubectl-helm:<tag>`

Images tags are equal to kubectl version.

**helm**
```
docker run ricsanfre/docker-kubectl-helm helm
```
**kubectl**
```
docker run ricsanfre/docker-kubectl-helm kubectl
```