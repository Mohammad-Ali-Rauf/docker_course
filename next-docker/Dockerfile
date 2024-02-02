FROM node
WORKDIR /app
COPY package*.json .
RUN yarn
COPY . /app/
EXPOSE 3000
CMD yarn dev
