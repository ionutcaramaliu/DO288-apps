FROM node:14

EXPOSE 3000

COPY . .

RUN npm install express

RUN npm install mysql

CMD mysql -uuser -p < test.sql
