FROM node:20-alpine

WORKDIR /kaur_arshpreet_site

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]