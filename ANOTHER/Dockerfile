FROM almalinux:9 
ENV name="kedarnath" \
    purpose="env_latest" \
    description="accessing inside the container"
LABEL author="mahesh" \
        purpose="latest-nginx" \
        description="to deploy frount end "
RUN dnf install nginx -y 
CMD  ["nginx", "-g", "daemon off;"]
EXPOSE 80/tcp 