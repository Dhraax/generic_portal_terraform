FROM node:14-alpine

RUN apk add g++ make py3-pip

RUN npm install -g npm@7.20.2

WORKDIR /src

COPY package*.json ./

RUN npm ci

COPY . ./
