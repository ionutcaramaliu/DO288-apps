FROM mysql

COPY . .

RUN install-package mysql

CMD mysql -uuser -p < test.sql
