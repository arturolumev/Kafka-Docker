<ol>
  <li>docker-compose up</li>

  <li>docker exec -it kafka-broker-1 bash</li>
  
<li>Crear topico: kafka-topics --bootstrap-server kafka-broker-1:9092 --create --topic practica-2</li>
  
<li>Crear el producer: 
  kafka-console-producer --bootstrap-server kafka-broker-1:9092 --topic practica-2</li>
  
<li>Crear el consumidor: 
kafka-console-consumer --bootstrap-server kafka-broker-1:9092 --topic practica-2 --from-beginning</li>
</ol>
