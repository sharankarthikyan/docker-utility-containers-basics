## CMD vs. ENTRYPOINT

### CMD

> Adding CMD in runtime will override the existing CMD in the image file.

### ENTRYPOINT

> Adding CMD in runtime will append on the ENTRYPOINT specified in the image.

$ `docker build -t mynpm .`

$ `docker run -it -v /Users/sharan/Desktop/Sharan/Git/docker-utility-containers:/app mynpm install express`
