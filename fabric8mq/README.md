runs a Fabric8 MQ broker based on [Apache ActiveMQ](http://activemq.apache.org/) which is then exposed as a [kubernetes service](http://fabric8.io/v2/services.html) so that clients can easily connect.

Note that this pod requires a running amqbroker container. Alternatively there is an 'amq' package that will start up both this container and the amqbroker.
