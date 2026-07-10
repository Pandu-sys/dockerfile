FROM almalinux:9
RUN dnf install nginx -y
RUN em -rf /usr/share/nginx/html/*
ONBUILD COPY src /usr/share/nginx/html/
CMD [ "nginx", "-g", "daemon off;"]
