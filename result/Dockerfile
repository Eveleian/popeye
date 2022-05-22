FROM node:12-alpine

WORKDIR /app
RUN apk add --update nodejs npm
ADD src /app

RUN npm install

EXPOSE 80
CMD node server.js