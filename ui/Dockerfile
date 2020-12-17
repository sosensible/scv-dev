FROM node:14.15.2
LABEL Name=vuejs Version=0.0.1

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["node", "app.js"]
