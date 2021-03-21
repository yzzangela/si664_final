# si664_final

I will be making a real-time chat application using Django, RabbitMQ (an open source message broker), Vue.js (javascript framework) and uWSGI (websocket server). Users will be able to send messages to one another synchronously. 

When a user sends a message through the application's interface (Vue.js), Django will then take the message through the API, which will then be forwarded to RabbitMQ. RabbitMQ will then broadcast the messages to multiple queues (uWSGI), which are communication channels that would eventually deliver the messages to the clients. 
