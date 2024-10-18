FROM node:20
EXPOSE 8080
RUN useradd expense 
RUN mkdir /app
ADD https://expense-builds.s3.us-east-1.amazonaws.com/expense-backend-v2.zip /tmp/backend.zip
WORKDIR /app
RUN unzip /tmp/backend.zip
RUN npm install
CMD [ "sleep", "100" ]

