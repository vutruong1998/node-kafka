FROM node:14-alpine

MAINTAINER Vu Cong Truong <vucongtruong1998@gmail.com>

WORKDIR /src

COPY package*.json ./

RUN yarn install

COPY . .

CMD ["yarn", "dev"]