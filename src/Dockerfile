FROM node:20.15-alpine3.19 

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 8080/tcp
ENTRYPOINT [ "node", "server.js" ]