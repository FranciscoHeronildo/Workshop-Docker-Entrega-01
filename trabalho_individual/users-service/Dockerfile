FROM node:alpine

WORKDIR /users-service

RUN yarn

COPY package.json ./
COPY yarn.lock ./

COPY . .

EXPOSE 7101

CMD ["yarn", "watch"]
