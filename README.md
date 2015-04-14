## Java Microservices Demo
**_This project is still in early stage development_**

Java-based microservices demonstration, using [RestExpress](https://github.com/RestExpress), MongoDB, AngularJS, and HAProxy.

#### Virtual Vehicle Application
The 'Virtual Vehicle' application allows a user to create a collection of virtual vehicles, maintain their vehicles, and use a virtual valet service to park the their vehicles. The 'Virtual Vehicle' application uses an AngularJS-based web UI to call three, load-balanced, highly-available, Java EE, RestExpress-based microservices. Following current microservice architectural patterns, each service has it's own MongoDB data-source.
* Vehicle Service (virtual_vehicle database)
* Maintenance Service (virtual_maintenance database)
* Valet Service (virtual_valet database)

#### Technologies Used
* [RestExpress](http://search.maven.org/#artifactdetails%7Ccom.strategicgains.archetype%7Crestexpress-mongodb%7C1.15%7Cmaven-archetype)
* MongoDB
* AngularJS
* HAProxy
* [Netty](http://netty.io/)
* Java EE, Maven, NetBeans
* VirtualBox, Foreman, Puppet, Jenkins

#### RestExpress
According to their website, [RestExpress](https://github.com/RestExpress) composes best-of-breed open-source tools to enable quickly creating RESTful microservices that embrace industry best practices. Built from the ground-up for container-less, microservice architectures, RestExpress is the easiest way to create RESTful APIs in Java. An extremely Lightweight, Fast, REST Engine and API for Java. A thin wrapper on Netty IO HTTP handling, RestExpress lets you create performant, stand-alone REST APIs rapidly.