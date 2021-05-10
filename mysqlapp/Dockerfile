FROM mysql

COPY . .

RUN install mysql

CMD ["mysql -uuser -p < test.sql"]
