# Use an existing docker image as a base
FROM alpine

# download and install a dependency
RUN apk add --update redis
RUN apk add --update gcc

# Tell the image what do when it starts
# as a container

CMD [ "redis-server" ]