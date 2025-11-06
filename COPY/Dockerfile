FROM almalinux : 9
RUN dnf install nginx -y
RUN rm -f /usr/share/nginx/index.html
COPY index.html /usr/share/nginx/index.html
CMD ["nginx", "-g", "daemon off;"]