FROM node:16.20.2
LABEL authors="Codeur16"

WORKDIR /app

COPY package*.json ./
COPY . .

RUN npm install


EXPOSE 4002

CMD ["npm", "start"]