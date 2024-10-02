FROM almalinux:9
RUN dnf install nginx -y
RUN cd /usr/share/nginx/html
RUN rm -rf *
RUN mkdir index.html
WORKDIR /index.html
COPY index.html /usr/share/nginx/html/index.html
