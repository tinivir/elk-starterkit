FROM docker.elastic.co/beats/metricbeat:6.1.1

USER root

ADD config/metricbeat.yml /usr/share/metricbeat/metricbeat.yml

RUN chmod go-w /usr/share/metricbeat/metricbeat.yml
