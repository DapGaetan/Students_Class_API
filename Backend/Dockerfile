FROM node:14

WORKDIR /app/Backend

COPY package.json ./

RUN npm install

COPY . .

CMD ["node", "server.js"]
