FROM node:alpine

WORKDIR /app

COPY ./packaga.json ./

RUN npm install

COPY . .

CMD ["npm", "run", "start"]