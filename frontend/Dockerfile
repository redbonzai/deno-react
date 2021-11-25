FROM node:16.13.0-alpine3.13

WORKDIR /usr/app

COPY package.json ./
COPY yarn.lock ./

RUN yarn install
#CMD ["yarn", "start"]

COPY . .
