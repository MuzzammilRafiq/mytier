FROM node:18

WORKDIR /app

COPY package*.json ./
COPY pnpm-lock.yaml ./

RUN npm install -g pnpm

RUN pnpm i

COPY . ./

CMD [ "pnpm" ,"start" ]

