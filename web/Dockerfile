FROM nginx 
EXPOSE 80
RUN rm -rf /usr/share/nginx/html/*
COPY code/* /usr/share/nginx/html/
COPY expense.conf /etc/nginx/default.d/expense.conf
#CMD [ "nginx", "-g", "daemon off;" ]
