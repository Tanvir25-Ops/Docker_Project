FROM node:latest 

WORKDIR /app

COPY ./react_app/package*.json ./

RUN npm install

COPY ./react_app .

RUN npm run build

CMD ["npm", "start"]

EXPOSE 3000
