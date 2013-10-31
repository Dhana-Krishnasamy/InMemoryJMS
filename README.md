InMemoryJMS
===========

Inter-Thread communication library confirming to JMS Interface.


How to use it
=============
1) Include the jar in your project classpath
2) Use the following APIs on Broker class to create 
    a) Queue Sender (BrokerFactory.createSender(QueueName))
    b) Queue Receiver (BrokerFactory.createReceiver(QueueName))
    c) Topic Publisher (BrokerFactory.createPublisher(QueueName))
    d) Topic Subscriber (BrokerFactory.createSubscriber(QueueName))
    Or Take a look at demo project
