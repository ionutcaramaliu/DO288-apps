FROM node:14

LABEL taskmysql7 true

EXPOSE 3000

COPY . .

RUN npm install express

RUN npm install mysql

CMD node server.js
