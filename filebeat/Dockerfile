ARG ELASTIC_VERSION
FROM docker.elastic.co/beats/filebeat:${ELASTIC_VERSION}
COPY --chown=root:filebeat config/filebeat.yml /usr/share/filebeat/filebeat.yml
USER root