#required because the frontend is based on node
FROM node 

WORKDIR /app

COPY package.json . 

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "npm", "start" ] 