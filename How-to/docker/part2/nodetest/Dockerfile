FROM node:12

WORKDIR /usr/src/nodetest

COPY package*.json ./

RUN npm i -g nodemon

RUN npm install

COPY . .

EXPOSE 3000 3000

CMD ["npm", "run", "start:dev"]