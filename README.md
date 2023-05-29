# GC Tuning in containers

This repo contains the setup code used to showcase during the devday for GC tuning.

### Pre-requisite
- Docker
 if you are using the colima then you have to set below environment,

```
export DOCKER_HOST="unix://$HOME/.colima/docker.sock"
```

To build the image,

```
 ./gradlew dockerBuildImage
```