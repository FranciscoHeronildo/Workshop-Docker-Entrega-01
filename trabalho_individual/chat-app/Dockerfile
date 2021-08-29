FROM node:alpine

WORKDIR /chat-app

RUN yarn

COPY package.json ./
COPY yarn.lock ./

COPY . .

EXPOSE 7001

CMD ["yarn", "watch"]
