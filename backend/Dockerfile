FROM node

WORKDIR /app

RUN npm init

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["npm", "start"]