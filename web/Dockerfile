FROM nginx 
EXPOSE 80
RUN rm -rf /usr/share/nginx/html/*
ADD https://expense-builds.s3.us-east-1.amazonaws.com/expense-frontend-v2.zip /tmp/frontend.zip
CMD [ "sleep", "200" ]