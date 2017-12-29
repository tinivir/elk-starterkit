FROM docker.elastic.co/beats/filebeat:6.1.1
USER root
ADD filebeat.yml /usr/share/filebeat/filebeat.yml
COPY filebeat.yml /usr/share/filebeat/filebeat.yml 
RUN chmod go-w /usr/share/filebeat/filebeat.yml
