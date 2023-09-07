# Microservice application using Go

Web application that connects to 5 microservices.

### How to run:

front-end: go run ./cmd/web

broker: go run ./cmd/web

## Functionality:
- Receiving requests from front-end
- Authentication with Postgres
- Logger with MongoDB
- Sending emails
- Message consumer with RabbitMQ

## Technologies:
- Rest API with JSON
- RPC and gRPC
- Docker
- MongoDB, Postgres, RabbitMQ
- AMQP (Advanced Message Queuing Protocol)