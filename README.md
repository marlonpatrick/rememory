**Project for personal studies purpose  in several areas of software development, especially distributed systems, devops, cloud, microservices, containers.**

# Rememory

With this application, you can save your personal memories (text, photo, audio, video, etc.) and receive random notifications to remember.

Some social networks like Facebook have similar functionality, however, the idea of this application is that your memories are private. Other apps like Google Photos work only with photos or videos, but do not deal with texts or audios.

Some ideas on how to use Rememory:

- Remember special moments such as birthdays, weddings, children's development, etc;
- Remember something that motivates or inspires you;
- Remember a dream or plan that you might end up forgetting about the daily routine;
- Remember a quote from a book;
- Remember a tip, information, knowledge, advice, etc;

## Related Repositories/Projects


- [Project Backlog](https://github.com/users/marlonpatrick/projects/4)
- [Remembrance Management](../../../rememory-remembrance-management): service responsible to expose APIs to register remembrances
- [Outbox Transformer](../../../kafka-mongodb-outbox-transformer): a Kafka Streams application responsible for transform a MongoDB "raw change stream document" into a standardized message format to implement the [Transactional Outbox Pattern](https://microservices.io/patterns/data/transactional-outbox.html) with MongoDB and Kafka.
- [Outbox Remover](../../../kafka-mongodb-outbox-remover): a Kafka Consumer application responsible for remove outbox messages from MongoDB after messages arrived in Kafka. May be used in a strategy to implement [Transactional Outbox Pattern](https://microservices.io/patterns/data/transactional-outbox.html) with MongoDB and Kafka.
