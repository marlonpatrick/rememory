**Project for personal studies purpose  in various areas of software development, especially distributed systems, devops, cloud, microservices, containers.**

# Rememory

With this application, you can save your personal memories (text, photo, audio, video, etc.) and receive random notifications to remember.

Some social networks like Facebook have similar functionality, however, the idea of this application is that your memories are private. Other apps like Google Photos work only with photos or videos, but do not deal with texts or audios.

Some ideas on how to use Rememory:

- Remember special moments such as birthdays, weddings, children's development, etc;
- Remember something that motivates or inspires you;
- Remember a dream or plan that you might end up forgetting about the daily routine;
- Remember a quote from a book;
- Remember a tip, information, knowledge, advice, etc;

## Completed study goals


#### 2020.2

- Implement a pratical Hexagonal/Clean Architecture in a Spring Boot application
- Understand and configure several tools from the Kafka ecosystem (Connect, Schema Registry, Rest Proxy, UI apps) for a development environment with docker compose
- Understand and configure MongoDB for a development environment with docker compose
- Implement a Kafka Connect Source (MongoDB to Kafka)
- Implement a Kafka Consumer application
- Implement a Kafka Streams  application
- Implement the [Transactional Outbox Pattern](https://microservices.io/patterns/data/transactional-outbox.html) with MongoDB and Kafka


## Related Repositories/Projects

- [Remembrance Management](https://github.com/marlonpatrick/rememory-remembrance-management): service responsible to expose APIs to register remembrances
- [Outbox Transformer](https://github.com/marlonpatrick/kafka-mongodb-outbox-transformer): a Kafka Streams application responsible for transform a MongoDB "raw change stream document" into a standardized message format to implement the [Transactional Outbox Pattern](https://microservices.io/patterns/data/transactional-outbox.html) with MongoDB and Kafka.
- [Outbox Remover](https://github.com/marlonpatrick/kafka-mongodb-outbox-remover): a Kafka Consumer application responsible for remove outbox messages from MongoDB after messages arrived in Kafka. May be used in a strategy to implement [Transactional Outbox Pattern](https://microservices.io/patterns/data/transactional-outbox.html) with MongoDB and Kafka.
