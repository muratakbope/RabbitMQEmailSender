# Program for Sending emails using RabbitMQ

### Stack of technology used in this project

| Name          | Version                                                          |
|---------------|------------------------------------------------------------------|
| Spring boot   | 3.2.3                                                            |
| Java          | Java 17 Amazon Coretto                                           |
| Maven         | 3                                                                |

```http 
    docker pull rabbitmq:3.10-managment
```

```http
    docker run --rm -it -p 15672:15672 -p 5672:5672 rabbitmq:3.10-management
```