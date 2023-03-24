FROM node:10-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

RUN npm i dotenv

COPY . .

EXPOSE 3001

CMD ["node", "server.js"]
