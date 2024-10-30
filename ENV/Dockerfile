FROM almalinux:9
ENV trainer="kedarnath" \
    course="devops" \
    description="helps in access inside the container"
LABEL author="kedarnath" \
      purpose="env" \
      description="latest file "
RUN dnf install nginx -y 
CMD  ["nginx", "-g", "daemon off;"]
EXPOSE 80/tcp 