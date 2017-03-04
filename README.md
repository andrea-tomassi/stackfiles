# stackfiles
Collection of stackfiles for Docker Cloud staks

## [kafka.yaml](https://github.com/andrea-tomassi/stackfiles/blob/master/kafka.yaml)
Contains a full Kafka stack working out of the box.

The only parameter you need to valorize is: `KAFKA_ADVERTISED_HOST_NAME=###`

This Stackfile will deploy: **zookeeper, kafka, kafka-rest, schema-registry and kafka-connector**.

Kafka Connectors service needs to be parametrized accordingly to your needs. Look at [Kafka Connect Tutorial](http://docs.confluent.io/3.0.1/cp-docker-images/docs/tutorials/connect-avro-jdbc.html?highlight=docker).

## [graylog.yaml](https://github.com/andrea-tomassi/stackfiles/blob/master/graylog.yaml)
This file will deploy a fully working single instance Graylog server, with mongoDB and elasticsearch. 
