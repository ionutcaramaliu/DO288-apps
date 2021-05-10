FROM mysql

COPY . .

RUN app install mysql

CMD ["mysql -uuser -p < test.sql"]
