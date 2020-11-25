**Project for personal studies purpose  in various areas of software development, especially distributed systems, devops, cloud, microservices, containers.**

With this application, you can save your personal memories (text, photo, audio, video, etc.) and receive random notifications to remember.

Some social networks like Facebook have similar functionality, however, the idea of this application is that your memories are private. Other apps like Google Photos work only with photos or videos, but do not deal with texts or audios.

Some ideas on how to use Rememory:

- Remember special moments such as birthdays, weddings, children's development, etc;
- Remember something that motivates or inspires you;
- Remember a dream or plan that you might end up forgetting about the daily routine;
- Remember a quote from a book;
- Remember a tip, information, knowledge, advice, etc;

**Completed study goals**


- Implement a pratical Hexagonal/Clean Architecture in a Spring Boot application
- Understand and configure several tools from the Kafka ecosystem (Connect, Schema Registry, Rest Proxy, UI apps) for a development environment with docker compose
- Understand and configure MongoDB for a development environment with docker compose
- Implement a Kafka Connect Source (MongoDB to Kafka)
- Implement a Kafka Consumer application
- Implement a Kafka Streams  application


**Related Repositories/Projects**

- [Remembrance Management](https://github.com/marlonpatrick/rememory-remembrance-management): service responsible to expose APIs to register remembrances
- [Outbox Transformer (kafka Streams)](https://github.com/marlonpatrick/kafka-mongodb-outbox-transformer): a Kafka Streams application responsible for transform a MongoDB "raw change stream document" into a standardized message format to implement the [Transactional Outbox Pattern](https://microservices.io/patterns/data/transactional-outbox.html) with MongoDB and Kafka.
