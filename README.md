# Tutorial 8 ˚˖𓍢ִ໋🦢˚
## Nabiilah Putri Safa - 2206030426
-----------------------------------

a. what is amqp?

AMQP stands for Advanced Message Queuing Protocol. It's an open standard application layer protocol for message-oriented middleware. Essentially, it's a protocol used for communicating between applications or services, particularly in scenarios where there's a need for asynchronous communication, reliable messaging, and queuing.

AMQP is designed to enable different software systems to communicate with each other in a reliable, secure, and interoperable way. It provides features such as message queuing, routing, reliability, and security, making it suitable for various use cases such as distributed systems, microservices architecture, and enterprise messaging.

One of the key features of AMQP is its flexibility and interoperability, allowing different messaging systems and software implementations to communicate seamlessly as long as they support the protocol.

b. what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for? 

In the context of "guest:guest@localhost:5672", each part represents different components of connecting to an AMQP server:

"guest:guest": This part represents the username and password used for authentication. In this case, "guest" is both the username and the password. It's a common default configuration for some AMQP servers, used mainly for testing or development purposes. In a production environment, you would typically use more secure credentials.
"localhost:5672": This part represents the hostname and port number of the AMQP server. "localhost" refers to the local machine, meaning that the AMQP server is running on the same machine where this connection is being established. "5672" is the default port number for AMQP connections.
So, putting it all together, "guest:guest@localhost:5672" means connecting to an AMQP server running on the local machine, using the username and password "guest" for authentication, and communicating over port 5672.

![Screenshot 2024-04-24 154618](https://github.com/nabiilahputri13/html-portfolio/assets/124870275/68abe185-3fa8-4fbb-9dd8-dfab928d5ee7)
**Simulation slow subscriber**

This occurs because the subscriber requires more time to process the queue, resulting in message accumulation.

