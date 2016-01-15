# ActiveMQ Perf: AMQP Perf Test
Extending the `activemq-perf-maven-plugin` to use AMQP.

The documentation for the `activemq-perf-maven-plugin` still applies and can be found here:

[http://activemq.apache.org/activemq-performance-module-users-manual.html](http://activemq.apache.org/activemq-performance-module-users-manual.html)

This project provides a custom `SPIConnectionFactory` to allow creation of an AMQP `JmsConnectionFactory`. The documentation for the `AMQPReflectionSPIConnectionFactory` properties (ie, factory.remoteURI, ...) can be found at:

[https://qpid.apache.org/releases/qpid-jms-0.5.0/docs/index.html](https://qpid.apache.org/releases/qpid-jms-0.5.0/docs/index.html)