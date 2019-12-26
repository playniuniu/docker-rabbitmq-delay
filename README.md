# Docker for RabbitMQ Delayed Message Plugin

### Run

```shell
docker run --hostname mq -e RABBITMQ_DEFAULT_USER=user -e RABBITMQ_DEFAULT_PASS=passwd -p 5672:5672 -p 15672:15672 -d playniuniu/rabbitmq:3.8-management-alpine
```

### Refer
[构建 RabbitMQ With Plugins](https://anoyi.com/p/743ff70f6413)
