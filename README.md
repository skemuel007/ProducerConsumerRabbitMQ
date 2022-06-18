# Producer Consumer with RabbitMQ
Simple console application with producer and consumer side using rabbitmq factory to create connection from .net core 3.1 application, producing a message by a sender with a receiver consuming the message.
## Technology
.NET 3.1 Console Application, RabbitMQ and Docker

## Setup
> Ensure dotnet core 3.1 is installed on your local machine, also ensure docker desktop is installed as well
> Run rabbitmq using docker command `docker run -d --hostname rabbitmq --name rabbit-mq -p 5672:5672 -p 9090:15672 rabbitmq:3-management`
> Open your browser and enter the address `localhost:9090`
> Use user name: ***guest*** and password ***guest*** to connect
> N/B: rabbitmq exposes port ***5672*** for *amq* connection by dotnet core
> Navigate into the project folder and Run the command `dotnet run`