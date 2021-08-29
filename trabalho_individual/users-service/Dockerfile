FROM node:alpine

WORKDIR /chat-app

COPY package.json ./
COPY yarn.lock ./

COPY . .

EXPOSE 7101

CMD ["yarn", "db:migrate", "watch"]
