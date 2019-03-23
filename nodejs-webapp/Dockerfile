# Specify a base image
FROM node:alpine

WORKDIR /usr/app

# Install some dependancies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]