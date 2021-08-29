FROM node:alpine

WORKDIR /chat-app

COPY package.json ./
COPY yarn.lock ./

COPY . .

CMD ["yarn", " yarn watch"]
