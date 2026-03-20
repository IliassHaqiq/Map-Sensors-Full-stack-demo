FROM node:20-alpine

WORKDIR /app

COPY backend/package.json ./
RUN npm install

COPY backend/server.js ./
COPY data /app/data

EXPOSE 5000

CMD ["npm", "start"]