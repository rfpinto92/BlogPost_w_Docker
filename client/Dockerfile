FROM node:14-slim

WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install --save --legacy-peer-deps
COPY . .

EXPOSE 3000

CMD [ "npm","start" ]