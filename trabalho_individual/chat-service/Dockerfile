FROM node:alpine

WORKDIR /chat-app

COPY package.json ./
COPY yarn.lock ./

COPY . .

EXPOSE 7100

CMD ["yarn", "watch"]
