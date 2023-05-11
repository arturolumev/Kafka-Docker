1- docker-compose up

2- docker exec -it kafka-broker-1 bash
3- Crear topico
kafka-topics --bootstrap-server kafka-broker-1:9092 --create --topic practica-2
4- Crear el producer
kafka-console-producer --bootstrap-server kafka-broker-1:9092 --topic practica-2
5- Crear el consumidor
kafka-console-consumer --bootstrap-server kafka-broker-1:9092 --topic practica-2 --from-beginning

