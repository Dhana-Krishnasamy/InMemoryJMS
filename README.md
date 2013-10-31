InMemoryJMS
===========

Inter-Thread communication library confirming to JMS Interface.

<br>
How to use it
=============
<ol>
 <li>Include the jar in your project classpath</li>
 <li>
 Use the following APIs on Broker class to create 
     <ol>
        <li>Queue Sender (BrokerFactory.createSender(QueueName))</li>
         <li>Queue Receiver (BrokerFactory.createReceiver(QueueName))</li>
         <li>Topic Publisher (BrokerFactory.createPublisher(QueueName))</li>
         <li>Topic Subscriber (BrokerFactory.createSubscriber(QueueName))</li>
         <li>Or Take a look at demo project</li>
        </ol>
    </li>
</ol>

Some of the features 
====================
<ul>
<li> Full JMS API compliance for Queue / Topic clients including timed receive etc </li>
<li> Automatic message expiry (slow consumers will not affect the performance) </li>
<li> Automatic resource clean up (Remove the topic if there are no publisher/subscriber etc) </li>
</ul>
