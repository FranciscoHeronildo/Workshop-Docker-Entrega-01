FROM node:alpine

WORKDIR /api-gateway

RUN yarn

COPY package.json ./
COPY yarn.lock ./

COPY . .

EXPOSE 7000

CMD ["yarn", "watch"]
