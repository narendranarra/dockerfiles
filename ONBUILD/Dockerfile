FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD COPY index.html /usr/share/nginx/html/index.html # i have removed index.html right so i expect while usimng my image there should be something in index.html
CMD ["nginx", "-g", "daemon off;"]