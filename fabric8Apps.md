## Fabric8 Apps

The following [Apps](apps.html) are included in the Fabric8 distribution.

* [Management](management.html)
    * [Console](console.html) provides a nice web application based on [hawtio](http://hawt.io/) for working with your [apps](apps.html), [pods](pods.html), [replication controllers]
    * [Logging](logging.html) provides consolidated logging and visualisation of log statements and events across your environment
    * [Metrics](metrics.html) provides consolidated historical metric collection and visualisation across your environment
(replicationControllers.html) and [services](services.html)
    * [App Library](appLibrary.html) provides a configurable library of Apps you can easily run and install or uninstall; rather like your library of Apps on a mobile device.
APIs in your cluster.
* [Continuous Delivery](cdelivery.html) 
    * [Chat](chat.html) provides a [hubot](https://hubot.github.com/) [app](apps.html) and a notification engine to post [build completion](builds.html) events to a chat room (which defaults to one room per kubernetes namespace).
* [iPaaS](ipaas.html) provides an _Integration Platform As A Service_  
    * [API Registry](apiRegistry.html) provides a global view of all of your RESTful and web service APIs that is displayed in the [Console](console.html) allowing you to inspect and invoke all the endpoints 
    * [MQ](fabric8MQ.html) implements _Messaging As A Service_ with [Apache ActiveMQ](http://activemq.apache.org/) on Kubernetes.
    * [MQ AutoScaler](fabric8MQAutoScaler.html) monitors and scales the [Apache ActiveMQ](http://activemq.apache.org/) brokers running on Kubernetes
