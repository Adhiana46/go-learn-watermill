## What is Watermill?
Watermill is a Golang library for working efficiently with message streams. It is intended for building event-driven applications. It can be used for event sourcing, RPC over messages, sagas, and whatever else comes to your mind. You can use conventional pub/sub implementations like Kafka or RabbitMQ, but also HTTP or MySQL binlog, if that fits your use case.

It comes with a set of Pub/Sub implementations and can be easily extended by your own.

Watermill also ships with standard middlewares like instrumentation, poison queue, throttling, correlation, and other tools used by every message-driven application.

## Why use Watermill?
With more projects adopting the microservices pattern over recent years, we realized that synchronous communication is not always the right choice. Asynchronous methods started to grow as a new standard way to communicate.

But while there’s a lot of existing tooling for synchronous integration patterns (e.g. HTTP), correctly setting up a message-oriented project can be a challenge. There’s a lot of different message queues and streaming systems, each with different features and client library API.

Watermill aims to be the standard messaging library for Go, hiding all that complexity behind an API that is easy to understand. It provides all you might need for building an application based on events or other asynchronous patterns. After looking at the examples, you should be able to quickly integrate Watermill with your project.

