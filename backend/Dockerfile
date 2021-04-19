FROM node:10-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install
COPY . .

EXPOSE 33001
CMD [ "node", "index.js" ]
