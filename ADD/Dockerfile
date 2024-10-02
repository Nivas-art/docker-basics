FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD file:///C:/Users/91709/Downloads/script1.sh sri
CMD ["nginx", "-g", "daemon off;"]