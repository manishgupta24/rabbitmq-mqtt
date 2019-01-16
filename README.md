# rabbitmq-mqtt

RabbitMq Dockerfile with MQTT plugin enabled


### Command to Run 

sudo docker run --rm -it -p 1883:1883 -p 8883:8883 -p 5672:5672 -p 15672:15672 -e RABBITMQ_DEFAULT_USER=user -e RABBITMQ_DEFAULT_PASS=password manish24/rabbitmq-mqtt:latest
