# Specify a base image
FROM node:alpine

WORKDIR /usr/app

# Breaking out company to reduce dependecy refresh
COPY ./package.json ./
RUN npm install

# Move primary application code into container
COPY ./ ./

CMD [ "npm", "start" ]