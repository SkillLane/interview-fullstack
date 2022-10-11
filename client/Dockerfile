FROM node:14-alpine

WORKDIR /usr/src/app/client

COPY yarn.lock ./

RUN yarn

EXPOSE 3000

CMD ["yarn", "dev"]