# use an existing docker image as a base
FROM alpine:latest

# Download and install dependencies
RUN  apk add --update redis


# Tell the image what to do
CMD ["redis-server"]