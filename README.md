# dockercomposes
Repository for docker compose projects

This project is meant to be a repository for docker compose files. 


# localstack
levantar el docker compose 
```
docker-compose up -d
```

Para crear una cola de sqs 
```
aws --endpoint-url=http://127.0.0.1:4576 sqs create-queue --queue-name test-queue
```

Listar las colas 
```
aws --endpoint-url=http://127.0.0.1:4566 sqs list-queues
```
