FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://learn.microsoft.com/en-us/purview/information-protection /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]