ARG version 
FROM almalinux:${version:-8}
ARG ${trainer=kedarnath}
ARG ${duration=3_months}
ARG ${course=Docker}
ARG user
ENV user=${user} \
    dev=hello 

RUN echo "trainer is ${trainer}, duration is ${duration}, & course is ${course}"
CMD [ "sleep","100" ]
