FROM node:16.20.2
LABEL authors="Codeur16"

WORKDIR /app

COPY package*.json ./
COPY . .

RUN npm install

COPY . .

EXPOSE 4000

CMD ["npm", "start"]