FROM node:12.1-alpine

WORKDIR /workspace
ADD db.json db.json
ADD server.js server.js
RUN npm install json-server

EXPOSE 3000