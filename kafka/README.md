docker-compose.yml

Creates application containing Multiple Docker containers used for Kafka Application. Kafka and Zookeeper are assumed to be running on a Hosted Platform like AWS MSK.

Services defined in compose file are as below

    KsqlDB-Server
    KsqlDB-CLI
    Schema Registry
    Schema Registry UI
    Kafka Connect
    Kafka Connect UI
    Kafka RestProxy
    Kafka Topics UI
    
Access KSQL DB through KSQLDB CLI using Below command

    docker exec -it ksqldb-cli ksql http://ksqldb-server:8088
