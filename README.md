# Kafka03
proyecto con @kafkaListener

llamada de prueba para kafkaspring:  

curl http://cbk51.com:8080/api/v1/kafka/publish?message=hello%20world

llamada de prueba para kafkajson:  

curl -d '{"is": "1", "firstName":"Marco","lastName":"Guado"}' -H "Content-Type: application/json" -X POST http://localhost:8080/api/v1/kafka/publish