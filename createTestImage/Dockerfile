# Use an existing Docker Image
FROM alpine 

# Download and Install dependency
RUN apk add --update redis 

# Tell the image what to do when it starts
CMD ["redis-server"]

# DOCKER_BUILDKIT=0 docker build . To disable Buildkit,
