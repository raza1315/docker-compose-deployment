FROM node:alpine

WORKDIR /backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4001

CMD ["npm","start"]
