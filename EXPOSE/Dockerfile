FROM almalinux:9 
LABEL author="mahesh" \
        purpose="latest-nginx" \
        description="to deploy frount end "
RUN dnf install nginx -y 
CMD  ["nginx", "-g", "daemon off;"]
EXPOSE 80/tcp 
