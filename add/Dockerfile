
FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/ParthuReddy31/docker/tree/main/run/Dockerfile /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD [ "nginx", "-g", "daemon off;" ]