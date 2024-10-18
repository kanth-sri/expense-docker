FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD="ExpenseApp@1"
RUN mkdir /tmp/sql
ADD https://expense-builds.s3.us-east-1.amazonaws.com/expense-backend-v2.zip  /tmp/sql
RUN unzip /tmp/sql/expense-backend-v2.zip