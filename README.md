# Docker golang image

Minimal alpine docker image for running go server binaries

# Usage

Just use as a base image for your docker image with a compiled golang binary
```
FROM kynrai/docker-go
ADD main /
CMD ["./main"]
EXPOSE 8080
```

# Automated build

The image is always available on docker hub <https://hub.docker.com/r/kynrai/docker-go/>
