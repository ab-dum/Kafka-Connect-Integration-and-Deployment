FROM confluentinc/cp-server-connect-operator:6.1.6.0 AS base

USER root

RUN confluent-hub install --no-prompt confluentinc/kafka-connect-azure-blob-storage:1.6.16 \
    && confluent-hub install --no-prompt confluentinc/kafka-connect-azure-blob-storage-source:2.5.7

USER user