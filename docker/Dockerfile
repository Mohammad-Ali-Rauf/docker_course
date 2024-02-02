FROM node:20-alpine

WORKDIR /app

COPY . .

RUN npm init -y

RUN npm install -g typescript

RUN sh -c tsc hello.ts

CMD ["sh", "-c", "while true; do node hello.js; done"]
