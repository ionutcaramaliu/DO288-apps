FROM mysql

COPY . .

RUN npm install mysql

CMD ["mysql -uuser -p < test.sql"]
