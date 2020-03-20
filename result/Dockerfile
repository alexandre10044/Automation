FROM node:10

MAINTAINER Alexandre Frydman "@@epitech.eu"

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 35069

CMD [ "node", "server.js" ]