# Spring JMS Demo 

**A Spring Framework demo using the Java Messaging Service**

In summary, this project contains a message sender that wakes up every 2 seconds and uses a JMS Template to convert a Java object to JSON and send it to a pre-defined queue.

The JSON goes to an embedded server. The moment the JSON is put on the queue, it becomes available for a client listening on that queue and gets delivered exactly once.