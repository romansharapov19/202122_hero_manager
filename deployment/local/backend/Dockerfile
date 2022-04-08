FROM node:alpine

WORKDIR /app/backend

COPY package.json .

RUN npm install -g nodemon
RUN npm install

ENTRYPOINT [ "nodemon", "src/" ]