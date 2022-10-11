FROM node:14-alpine

WORKDIR /usr/src/app/api

COPY yarn.lock ./

RUN yarn

EXPOSE 4000

CMD ["yarn", "dev"]
