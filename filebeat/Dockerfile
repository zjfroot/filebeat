FROM docker.elastic.co/beats/filebeat:5.6.4
USER root
COPY filebeat.yml /usr/share/filebeat/filebeat.yml
RUN chown root /usr/share/filebeat/filebeat.yml
RUN chmod go-w /usr/share/filebeat/filebeat.yml
CMD ["./filebeat", "-e"]