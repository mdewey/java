# Java Jamboree in 6hrs

## Questions

> What version of Java?

I am seeing everything from Java 8 to Java 14, with everything in between. I am always of the opinion latest

I am also seeing a big split between Spring 4 and 5.

> Preferred IDE?

IntelliJ is the community preferred, there are ways to get free licence for boot camps. Can we do that or should we stick with free options.

> Is there a micro-level cadence?

Does the 6 hr workshop have a preferred scheduled (breaks, lunch, etc)?

> For these workshops, What is more important, knowledge or practice?

Do we want to the students to be exposed to more, but has less practice or less exposure and more practice.

> What format do you want for the markdown?

I assume this will be when we chat about the LMS.

> How public is this?

Is this repo cool? Can I run this past other alumni / community members I might know?

> Is there any Java curriculum currently?

Other internal resources?

## Elevator Pitch

Boot camp grads are coming into the market with a strong development foundation, but are lacking market needed skills. This course aims to offer a launch pad for a graduate to skill up in modern Java. This is a 6 hr whirlwind tour of Java the language, and Spring MVC, the modern way to create RESTful APIs.

## Learning Outcomes

- Understand what Java is
- Understand the basic philosophy behind Java
- be able understand basic Java syntax
- create simple console apps with Java
- Create a Spring Web API
- Know the next steps to continue learning Java

## Hardware

- A computer with
  - JDK 14(?)
  - git
  - Postgres 12(?)
- IntelliJ(?) install

_NOTE: Instructor will be using a Mac, but any platform is alright_

## Prerequisites

- Have created a RESTful API with out following tutorial
- Basic of programming
  - control statements
  - loops
  - Functions
  - Objects
- Familiarity with Objects and OOP
- Familiarity with SQL databases
- Git Knowledge
  - The phrase "clone this repo" doesn't scare you.
- Familiarity with React

## Lessons

### Installing Java

Will be in more detail at :[prework](prework.md)

### What is Java?

Will be in more detail at :[Lecture Notes](what-is-java.md)

- What is Java?
- Brief History
- What is the JVM?
- Why Java?
  - Garbage Collection
- Compiler
  - JIT
- JVM vs JDK vs JRE vs JIT

### Learning Java Foundation

Will be in more detail at :[Lecture Notes](java-basics.md)

- Simple Hello, World

  - parts of a simple program
  - I/O to standard in
  - variables
    - constants
    - Types
      - string
        - string concat
      - Numbers
      - Bool
      - Array/Maps/etc...
    - casting
  - control
    - if
    - loops

- Creating our own Objects
- What is OOP?
  - Ctors
  - scope
    - access modifiers
  - properties
    - getter
    - setters
    - static
  - methods
    - static
    - instance
    - Overloading
      - ToString for example
  - Inheritance
    - Abstract
    - Interfaces

### Brining Java to the web with Spring MVC

Will be in more detail at :[Lecture Notes](java-api.md)

- RESTful Review
- What is spring
- Why Spring
  - light wieght
  - IoC
  - MVC
  - Beans
- Creating a simple `Hello, World API`
- Swagger and packages
- Creating a
  - GET
  - POST
  - PUT
  - DELETE
- Configuration

### BONUS: Working with Databases

- What is SQL
  - Postgres
- Talk to a database
  - ORM (Hiberate)
  - No O

### Further topics

Will be in more detail at : [Hand out](postwork.md)

- String Builder and String Buffer
- Threading
- Exceptions
- Handling Files
- Sockets
- Servlets
- Collections
- Gradle
- Docker
- Micro-services
- Other JVM languages
- Android
- Exercism
