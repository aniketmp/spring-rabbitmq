## spring-rabbitmq-v3 ##

** Single Producer sending multiple messages to one exchange and that exchange is forwarding that message to multiple queues. We have to create multiple bindings between queue and exchange. Binding is nothing but the mapping between exchange and queue The no of bindings is equal to no of queues. Here single consumers listening on different queue receives messages. **