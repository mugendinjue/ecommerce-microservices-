# Micro-services
Microservices with Node.js and RabbitMQ

### RabbitMQ
---
- The most widely deployed open source message broker.
- RabbitMQ runs on many operating systems and cloud environments, and provides a wide range of developer tools for most popular languages.
- For more information on how to get started with RabbitMQ visit the official site [here](https://www.rabbitmq.com/getstarted.html)
- RabbitMQ is a message broker: it accepts and forwards messages. You can think about it as a post office: when you put the mail that you want posting in a post box, you can be sure that the letter carrier will eventually deliver the mail to your recipient. In this analogy, RabbitMQ is a post box, a post office, and a letter carrier .
- **Producing** means nothing more than sending. A program that sends messages is a **producer**.
- A **queue** is the name for a post box which lives inside RabbitMQ. Although messages flow through RabbitMQ and your applications, they can only be stored inside a queue. A queue is only bound by the host's memory & disk limits, it's essentially a large message buffer. Many producers can send messages that go to one queue, and many consumers can try to receive data from one queue. This is how we represent a queue.
- **Consuming** has a similar meaning to receiving. A **consumer** is a program that mostly waits to receive messages.
- > **Note** that the producer, consumer, and broker do not have to reside on the same host; indeed in most applications they don't. An application can be both a producer and consumer, too.
- > A producer is a user application that sends messages.
- > A queue is a buffer that stores messages.
- > A consumer is a user application that receives messages.