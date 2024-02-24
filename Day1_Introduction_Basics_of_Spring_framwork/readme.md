# Introduction to Spring and Spring Boot:
## 1. Spring framwork :
1. Introduction to Spring Framework
Spring Framework is a Java platform that provides comprehensive infrastructure support for developing Java applications. *Spring handles the infrastructure so you can focus on your application.*

Spring enables you to build applications from “plain old Java objects” (POJOs) and to apply enterprise services non-invasively to POJOs. This capability applies to the Java SE programming model and to full and partial Java EE.

Examples of how you, as an application developer, can use the Spring platform advantage:
* Make a Java method execute in a database transaction without having to deal with transaction APIs.
* Make a local Java method a remote procedure without having to deal with remote APIs.
* Make a local Java method a management operation without having to deal with JMX APIs.
* Make a local Java method a message handler without having to deal with JMS APIs.

2. Dependency Injection and Inversion of Control
  * Dependency Injection (DI) :
Dependency Injection is a design pattern used to implement Inversion of Control (IoC). It allows the creation of dependent objects outside of a class and provides those objects to a class in various ways. This approach makes classes less dependent on the specific implementation of their dependencies and makes it easier to manage dependencies, whether they're services, repositories, or configurations.

In Spring Framework, DI is achieved primarily through:
- Constructor Injection: Dependencies are provided through class constructors.
- Setter Injection: Dependencies are provided through setter methods or other configuration methods.
- Field Injection: Dependencies are injected directly into the fields of a class.
DI makes your code more modular, easier to test, and aligned with the principles of object-oriented design.

  * Inversion of Control (IoC) :
Inversion of Control is a broader principle where the control of objects or portions of a program is transferred to a container or framework. Instead of a developer manually controlling the flow of an application and creating objects, the framework takes over the job of orchestrating the various components of an application.

IoC can be achieved through various mechanisms, but Dependency Injection is one of the most common ways to achieve IoC in Spring Framework. With IoC, the Spring container will take care of instantiating, configuring, and assembling objects, and managing their life cycle.
3. Modules :
The Spring Framework consists of features organized into about 20 modules. These modules are grouped into Core Container, Data Access/Integration, Web, AOP (Aspect Oriented Programming), Instrumentation, and Test, as shown in the following diagram.
![Spring modules](/Ressources/spring_modules.png "Spring modules")
