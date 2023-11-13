FROM node:lts-alpine3.16

LABEL APP V2

COPY . /app

WORKDIR /app

EXPOSO 3000

RUN npm install

ENTRYPOINT [ "npm", "start" ]