# Introduction

### Overview

The Cargo Tracker project demonstrates how you can develop applications with the Java EE platform using widely adopted architectural best practices like Domain-Driven Design \(DDD\). The project is directly based on the well known original [Java DDD sample](http://dddsample.sourceforge.net/) application developed by DDD pioneer Eric Evans' company [Domain Language](http://domainlanguage.com/) and the Swedish software consulting company [Citerus](http://www.citerus.se/). The cargo example actually comes from Eric Evans' [seminal book](http://www.amazon.com/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215). That project uses older versions of Spring, Hibernate and Jetty whereas we focus on vanilla Java EE.

### Getting Started

Before exploring the code, it may be helpful to view a demo of the application functionality. You can do that through a [screen cast](http://git.delabassee.com/ct/demo.html) that covers most of the major functionality for Cargo Tracker.

The project is Maven based, so you should be able to easily build it or set it up in your favorite IDE. We currently have instructions for NetBeans.

You can also run the application directly from the Maven command line using Apache Cargo. All you need to is navigate to the project source root and type:

 `mvn package cargo:run`

Once the application starts up, just open up a browser and navigate to [http://localhost:8080/cargo-tracker/](http://localhost:8080/cargo-tracker/).

The project currently runs on Java EE 7/GlassFish 4 and Java SE 8 by default. You can also run the project using WebLogic 12.2.1 and Java SE 8 using [these instructions](http://git.delabassee.com/ct/WlsHowTo.html). We welcome contributions for running the application on other Java EE application servers \(as you will see in the source code, there are few dependencies on GlassFish or WebLogic so this should be pretty easy to do\).

Our roadmap \(see [these instructions](http://java.net/jira/browse/CARGOTRACKER)\) includes plans to create a Java EE 6 version of the application.

