FROM almalinux
# RUN yum install epel release -y 
RUN yum install nginx
RUN rm -rf /usr/sahre/nginx/html/index.html
COPY qi /usr/share/nginx/html
CMD ["nginx", "-g", "daemon off;"]