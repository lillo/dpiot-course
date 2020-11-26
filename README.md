# Distributed Programming for IoT (Lab)

**Teacher**: Letterio Galletta

**Contact**: *name.surname*(at)imtlucca.it

**Office hours**: contact me by e-mail

**Note that this page contains only the programming exercises,  all the material of the course is available on the Moodle page at** https://e-l.unifi.it/course/view.php?id=18192

## Course description

This course aims at providing an overview of the basic notions of distributed programming, with a focus on IoT systems. The course is divided into three parts. The first one presents how distributed systems are organized and basic communication mechanisms. The second part covers distributed computations, in particular the focus is on broadcast, election, consensus and coordination algorithms. The last part introduces the main application protocols used in the IoT systems, like MQTT and COAP.

## Learning objectives

After completing this course students will be able to understand and describe the architectural organization of both IoT systems and generic distributed ones. Students will be familiar with and will be able to explain and use high level communication mechanisms as e.g. Remote Procedure Call, RESTful APIs and message-oriented middle-ware, and to implement  distributed algorithms and evaluate their complexity. Moreover, students will be able to use standard protocols supporting communication among IoT components.

## Program of the course

The course will contain the following topics:
* Design goals of a distributed system
* Distributed system organization (software and system architecture)
* High level communication mechanisms (Remote Procedure Call and Message-oriented Middle-ware)
* Languages for Distributed System (KLAIM and Actor model)
* Distributed algorithms for broadcast, election, consensus, clock synchronization, logical clocks, mutual  exclusion
* IoT systems organization
* MQTT and COAP protocols

## Programming exercises
This table specifies the programming exercises with the relevant topics.

Remember to set up a Java programming environnement based on [Apache Maven](https://maven.apache.org/).

| Date  | Topics | Assignments|
| ------|------- |------------|
| 10/1  | Socket programming in Java    |  [Exercises 1](ex1/exercises1.org)  |
| 10/8  | Network programming in Java   |  [Exercises 2](ex2/exercises2.org)  |
| 10/15 | REST services in Jersey       |  [Exercises 3](ex3/exercises3.org)  |
| 10/22 | Java Remote Method Invocation |  [Exercises 4](ex4/exercises4.org)  |
| 10/29 | gRPC in Java                  |  [Exercises 5](ex5/exercises5.org)  |
| 11/12 | Basic distributed algorithm   |  [Exercises 6](ex6/exercises6.org)  |
| 11/19 | Algorithms for leader election|  [Exercises 7](ex7/exercises7.org)  |
| 11/26 | Protocol MQTT                 |  [Exercises 8](ex7/exercises8.org)  |
| 12/03 | ... | ... |

## Online resources
* [The Java Tutorial](https://docs.oracle.com/javase/tutorial/index.html)
* [Java Networking Tutorial](https://docs.oracle.com/javase/tutorial/networking/TOC.html)
* [Package java.net](https://docs.oracle.com/javase/8/docs/api/java/net/package-summary.html)
* An [interactive tutorial](https://learngitbranching.js.org/) on using `git`
* [Maven in 5 Minutes](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html)
* [The JBotSim Library](https://jbotsim.io/)
* [A quick tour of JBotSim](https://jbotsim.io/?p=examples/helloworld)
* [The JBotSim Documentation](https://jbotsim.io/javadoc/1.2.0/index.html?overview-summary.html)
