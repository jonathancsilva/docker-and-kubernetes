# Use an existing docker image as a base
FROM alpine

# Download and install a dependency
# RUN apk add --update gcc
RUN apk add --update redis

# Tell the image what to do when it starts as a container
CMD ["redis-server"]

# docker run -it alpine
# Inside
# apk add --update redis
# In another terminal, get de ID from container
# Generate new image
# docker commit -c 'CMD ["redis-server"]' XXXXX username/redis-server:latest