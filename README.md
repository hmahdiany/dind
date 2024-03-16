# Docker in Docker 
This is a Docker file which contains Docker engine and Docker compose addon. Purpose of creating this Docker image is for using in Gitlab CI/CD pipelines that using a runner with `docker` executor.

## How to use it
In order to use this image in Gitlab CI/CD pipeline add this config in `.gitlab-ci.yml`:
```
image:
  name: kinghossein/dind:v0.0.2
```
