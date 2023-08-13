# RabbitMQ microservices
An example project to create a basic microservice, using RabbitMQ, Docker and Go.

# Running Docker
```bash
docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management
```

# Used credentials
Rabbit credentials by default
__user__: guest, __password__: guest