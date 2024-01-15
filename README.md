
# Magoya Challenge Service

This project, provides functionality around Accounts and Transactions.


## Tech Stack

**API:**
Java 17 with Springboot 3.2.1

**Dependencies manager**: Maven

**Libraries:**
- Spring DataJPA,
- Spring DataMongoDB,
- Lombok
- Spring Web
- Spring AMQP
- Spring Validation


**Databases:**
- H2
- MongoDB
- PostgreSQL

## Installation

### Requirements
Before starting you need installed in your system
- Docker
- Docker compose

### Starting locally
Clone project

```bash
  git clone https://github.com/pccopa/magoya
```
Go to the project directory

```bash
  cd magoya
```

Executing project
Ensure that next ports are free to use to avoid missconfiguration

- 5432 	-> postgreSQL
- 27017 -> mongoDB
- 5672 	-> rabbitmq
- 15672 -> rabbitmq
- 8080	-> app accounts
- 8081	-> app listener

```bash
  docker compose up
```

## API Documentation

**Postman:**
You can find the [postman collection](Magoya Challenge.postman_collection.json) in this repo

Every single app has their own readme and help file please take a look before using this project
