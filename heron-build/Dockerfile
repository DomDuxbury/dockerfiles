FROM openjdk

COPY apache-storm-1.1.1.tar.gz /opt/storm.tar.gz
RUN tar -xf /opt/storm.tar.gz

ENTRYPOINT ["/apache-storm-1.1.1/bin/storm"]
