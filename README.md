# Docker-Commands
List of useful Docker Commands
 

| Command | Description |
| ------- | ----------- |
| `docker build -t <image_name>:1.0 .` | Build an image from the Dockerfile in the current directory and tag the image |
| `docker images` | List all images that are locally stored with the Docker engine |
| `docker rmi <image_name>:<tag_name>` | Delete an image from the local image store |
| `docker pull alpine:3.4` |  Pull an image from a registry |
| `docker tag alpine:3.4 myrepo/myalpine:3.4` | Retag a local image with a new image name and tag |
| `docker login my.registry.com:8000` | Log in to a registry (the Docker Hub by default) |
| `docker push myrepo/myalpine:3.4` | Push an image to a registry |
