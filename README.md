# Without docker-compose

## CMD vs. ENTRYPOINT

### CMD

> Adding CMD in runtime will override the existing CMD in the image file.

### ENTRYPOINT

> Adding CMD in runtime will append on the ENTRYPOINT specified in the image.

$ `docker build -t mynpm .`

$ `docker run -it -v /Users/sharan/Desktop/Sharan/Git/docker-utility-containers:/app mynpm install express`

---

# With docker-compose

$ `docker-compose run --rm mynpm init`

Syntax: `docker-compose run --rm <SERVICE_IN_DOCKER_COMPOSE> <CMD>`
