# Networked-Publisher-and-Subscriber-App
A  thread-safe networked Publish/Subscribe Broker pattern where Subscribers
subscribe to receive messages about a specific topic via the Broker. Publishers can publish messages
about specific topics, which are then forwarded via the Broker to all subscribers subscribed to those
topics. Subscribers can unsubscribe from a topic at any time and will then not receive any further
notifications.
A very important aspect of this was that Publishers and Subscribers did not know about each other
explicitly. Instead all communication was handled via a single, shared Broker object. In your
assignments, the Broker, Publishers and Subscribers were all within the same application and on the
same device.
