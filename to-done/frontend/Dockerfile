FROM node:12.18.3-alpine3.12

WORKDIR /usr/app

COPY package.json ./
COPY package-lock.json ./

RUN npm install

COPY . . 