FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Muralisanku/ansible/refs/heads/main/02-nginx.yaml /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx","-g","daemon off;"]