FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx//html/index.html
#this executes if any user use this as their base os
ONBUILD COPY index.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]