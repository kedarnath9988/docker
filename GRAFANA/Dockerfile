FROM ubuntu:22.04
RUN apt-get install -y apt-transport-https software-properties-common wget
RUN apt-get install grafana -y 
RUN apt-get install grafana-enterprise -y 
RUN systemctl enable grafana-server
RUN  systemctl start grafana-server.server


