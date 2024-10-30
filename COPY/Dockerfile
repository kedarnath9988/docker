FROM  almalinux:9 
ENV db_password="anolog"
LABEL author="kedarnath" \
        pupose="nginx "
RUN dnf install nginx -y 
RUN rm -f /usr/share/nginx/html/index.html 
COPY index.html  /usr/share/nginx/html/index.html 
CMD ["nginx","-g","daemon off;"]
EXPOSE 80
