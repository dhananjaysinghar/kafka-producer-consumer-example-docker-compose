## Run Zookeeper & Kafka in single command: 
~~~
docker compose -f ./kafka-config/docker-compose.yml up -d
(OR)
docker-compose -f ./kafka-config/docker-compose.yml up -d
~~~


## HTTP Request
~~~
curl --location --request POST 'http://localhost:8085/users' \
--header 'Content-Type: application/json' \
--data-raw '{
    "name": "dhananjaya",
    "mobile": "9040010697",
    "address": "Bangalore"
}'
~~~
