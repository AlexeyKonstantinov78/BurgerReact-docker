FROM node:18.14.0-alpine

WORKDIR /usr/app

COPY package*.json ./

RUN npm install

COPY . .
