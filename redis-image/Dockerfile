# Use existing docker image as a base: 
FROM alpine 

# Download and install a dependancy
RUN apk add --update redis

# Tell the image what to do on startup
CMD ["redis-server"]