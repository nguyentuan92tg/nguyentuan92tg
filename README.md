# Tuan Nguyen

Senior full-stack developer in Vietnam. For about twelve years I have taken software from design through production: Java services, React applications, and the integrations that sit between them.

I currently build [Casebook](https://casebook.net), a cloud SaaS platform that human-services organizations use to manage cases, client data, and service delivery. Before that I led delivery for a betting cash-out platform, an insurance workflow product, a mobile bank, and network-management systems used by clients in the US and Europe.

## How I work

Most of my time is on systems that have to stay configurable. Data creation, workflows, notifications, and persistence change per customer, so the design has to absorb that without a rewrite.

I work across the service boundary. On the backend that is Spring Boot, Spring Cloud, Spring Data, and Hibernate. On the frontend it is React, TypeScript, and Material UI, talking to the API through GraphQL and Apollo or through REST. I care about the contract between those sides: schema shape, what the client actually needs, and what fails when a downstream system is slow or wrong.

Quality is part of the design, not a phase at the end. I use the test pyramid in the pipeline (unit, contract, integration, and performance), review designs as well as code, and mentor people who are new to the codebase. The practices I keep coming back to are OOP, SOLID, clean code, TDD, and domain-driven design, applied where they earn their cost.

## Casebook

**Full Stack Developer** · May 2024 – present · Vietnam

Casebook is a multi-system SaaS product. Organizations configure how they create data, run workflows, send notifications, and store records. My work is to make that configuration real in the platform, and to keep the pieces consistent when a new integration is added.

- Lead design, integration, and implementation of enterprise features, then stay with them through delivery.
- Recommend how a new integration should sit in the existing architecture, against the business goal rather than only the nearest API.
- Specify and troubleshoot API integrations across the ecosystem when a flow breaks between services.
- Design for security and extension. The people whose data the platform holds are often in vulnerable situations, so access and change have to be deliberate.
- Work with stakeholders, partners, and engineers on the same problem, from the shape of the solution to the code that ships.

Java, Spring Boot, Spring Cloud, Spring Data, Hibernate, TypeScript, Node.js, React, Material UI, GraphQL, Apollo, PostgreSQL, Amazon RDS, Amazon SQS, Amazon S3, Kafka, Redis, Elasticsearch, Docker, Kubernetes, GitHub, and GitLab.

## Earlier work

### Lead Software Engineer, [EPAM Systems](https://www.epam.com)

Jan 2022 – Apr 2024 · Vietnam · customer: The Hong Kong Jockey Club

I led development of FO Cashout and its integration with Jacktime Betcore. The work had to stay correct under concurrency, and it had to stay available when the surrounding betting systems were under load.

- Produced high-level and detailed designs with solution architects and technical managers, and guided the architectural decisions that followed from them.
- Built the core cash-out functionality with an eye on performance, availability, and concurrency, not only the happy path.
- Designed a performance-testing tool for the cash-out flows so the team could load-test those functions instead of borrowing a generic harness.
- Ran design reviews and used them to tighten how the team made technical decisions.
- Supported engineers joining the team and kept knowledge in the group rather than in one person.

Java 17, Spring Boot, Spring Data, Spring Cloud Stream, Spring JMS, Hibernate, Microsoft SQL Server, Solace, Jenkins, Spinnaker, UrbanCode Deploy, AppDynamics, Docker, Kubernetes, JUnit 5, and Mockito. The design was event-driven and split into microservices.

### Technical Architect, [FPT Software](https://www.fptsoftware.com)

Jul 2021 – Jan 2022 · Vietnam · customer: Prudential Thailand

A web application that moved insurance data collection off paper and into a process the operations teams could run. I owned the technical shape of the product as well as feature delivery.

- Led feature development and kept the architecture aligned with what the client actually needed as the scope moved.
- Set up a project template so a new service started from a known structure instead of a copy of the last repository.
- Reviewed code against the practices the team had agreed, and used those reviews to raise the level of the people writing it.
- Built core functions and coached the team through the problems those functions exposed.

Java 17, Spring Boot, Spring Data, Spring JMS, Hibernate, Microsoft SQL Server, MySQL, Docker, and Kubernetes on Azure.

### Senior Software Engineer, [Axon Active](https://www.axonactive.com)

Apr 2018 – Jun 2021 · Vietnam

A mobile banking application. The product had to verify identity and generate documents as part of the customer journey, then stay fast enough that those steps did not become the bottleneck.

- Turned requirements into development objectives and drove the design and implementation of features.
- Reviewed code to hold a standard, and mentored newer engineers on that standard.
- Found and removed performance bottlenecks once the features were in use.
- Kept the release reliable: the banking flow is not a place to discover a broken contract in production.

Java, the Ivy framework, REST, PostgreSQL, Elasticsearch, HTML, CSS, JavaScript, jQuery, and Jenkins.

### Software Engineer, [TMA Solutions](https://www.tmasolutions.com)

Jan 2015 – Apr 2018 · clients in the US and Europe

Two network-management products, both with large teams.

**VitalQIP** (Feb 2015 – Oct 2017, about 50 people). Fixed defects, analyzed requirements, and built features. Maintained performance, wrote unit tests, and watched coverage and Sonar findings. Also trained people joining the team. Java, Spring, Hibernate, Qooxdoo, JavaScript, Oracle, REST, SOAP, plus C, C++, PL/SQL, and shell where the product needed them.

**VitalSuite** (Oct 2017 – Apr 2018, about 60 people). Built a template module and a public gateway API, and was the technical support for other members of the team. Spring Core, Spring AOP, Spring MVC, Spring Data, Spring Cloud, Hibernate, JDBC, and MySQL.

## Stack

| | |
| --- | --- |
| Languages | Java, TypeScript, JavaScript, SQL |
| Backend | Spring Boot, Spring Cloud, Spring Data, Spring Security, Hibernate |
| Frontend | React, Material UI, HTML, CSS |
| API | GraphQL, Apollo Client, REST, SOAP |
| Data | PostgreSQL, MySQL, SQL Server, Oracle, MongoDB, Redis, Elasticsearch |
| Cloud and delivery | AWS (RDS, SQS, S3), Azure, Docker, Kubernetes, Kafka, Solace, Jenkins, GitHub, GitLab |
| Testing | JUnit, Mockito, contract, integration, and performance tests |

## Education

Bachelor's degree, Computer Systems
Posts and Telecommunications Institute of Technology · 2010 – 2015

## Contact

[LinkedIn](https://www.linkedin.com/in/tuan-nguyen-0a5a1b106/)
