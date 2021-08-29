FROM node:alpine

WORKDIR /chat-service

COPY package.json ./
COPY yarn.lock ./

COPY . .

EXPOSE 7100

CMD ["yarn", "watch"]
