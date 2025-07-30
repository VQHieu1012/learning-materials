FROM flink:1.20.1

RUN wget https://dlcdn.apache.org/flink/flink-cdc-3.4.0/flink-cdc-3.4.0-bin.tar.gz -qO /opt/flink-cdc-3.4.0-bin.tar.gz && \
    tar xf /opt/flink-cdc-3.4.0-bin.tar.gz -C /opt && \
    mv /opt/flink-cdc-3.4.0 /opt/flink-cdc && \
    rm /opt/flink-cdc-3.4.0-bin.tar.gz