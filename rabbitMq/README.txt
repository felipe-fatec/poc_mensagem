docker run -d --hostname my-rabbit --name some-rabbit -p 8080:8080 -p 5672:5672 rabbitmq:3

rabbitmqctl list_queues

rabbitmqctl list_consumers

rabbitmqctl delete_queue hello
rabbitmqctl purge_queue hello