FROM node:14

WORKDIR /app/backend

COPY backend/package*.json ./

RUN npm install

COPY . .

CMD ["node", "server.js"]
