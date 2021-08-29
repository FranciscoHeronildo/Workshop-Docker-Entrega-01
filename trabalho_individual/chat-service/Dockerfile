FROM node:alpine

WORKDIR /chat-service

RUN yarn

COPY package.json ./
COPY yarn.lock ./

COPY . .

EXPOSE 7100

CMD ["yarn", "watch"]
