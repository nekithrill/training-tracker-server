FROM node:20-alpine

WORKDIR /server

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE ${SERVER_PORT}

CMD ["npm", "run", "dev"]