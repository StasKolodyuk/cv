# Stanislau Kaladziuk

## Overview
Lead Software Engineer with main focus in Java back-end development but also enthusiastic about other languages (Python, JavaScript and related frameworks, etc).
Experienced in cloud-native applications development, DevOps practices and microservices design.
Solid background in fintech domain.

## Personal Information

**Date of Birth:** 31.01.1995

**Foreign language:** Upper-Intermediate B2

## Education

**University:** BSU

**Faculty:** Applied Mathematics & Computer Science

**Period:** 2012 - 2018

**Diploma Specialty:** Distributed Systems

**Master Paper Specialty:** Computer Vision

## Professional Skills

**Languages:** 

Java 8-17, JS, Python 2-3, Bash

**Java Frameworks:** 

- Spring Umbrella Projects (Spring Boot 2, Spring Data, Spring MVC, Spring WebFlux, Spring JMS)
- Spring Cloud Umbrella Projects (Spring Cloud Config, Spring Cloud Function, Netflix OSS (Eureka, Ribbon, Hystrix))
- ORMs (JPA & Hibernate, Spring Data JPA, Spring Data JDBC, Spring JDBC)
- Build Tools (Gradle, Maven)
- Other (Netty client & server, Project Reactor, Lettuce, Swagger)

**JS Frameworks:** 

AngularJs, Yarn, Webpack

**Infrastructure:**

- Databases: Oracle 12c, DynamoDb, Redis, MongoDB
- AWS services: EC2, ECS, Fargate, Lambda, S3, SNS/SQS
- IAC: AWS CDK, Troposphere, Cloudformation
- Packer + Ansible basics

**Tools:**

- Git, Gitlab, Github, Bitbucket
- Docker & Docker Compose
- AWS Console & CLI
- Jenkins Pipelines & Gitlab CI
- Sonar Qube
- VisualVM, MAT, JConsole
- Postman
- DBeaver
- Intellij IDEA

## Past Projects

### Touchlane

#### CaaS Payment Platform

* Development of Card as a Service platform for banks and fintech companies.

**Customer**: Enfuce

**Project Role:** Team/Tech Leader, part of Architecture team

**Period:** Feb-2020 - Now

**Tasks performed:**

- Greenfield design, implementation & support of multiple (10+) APIs (Card issuing, Transaction Posting, Account, Customer, Exchange Rates etc.)
- Greenfield design, implementation & support of various "background jobs" as AWS Lambdas/AWS Batch (Fleet transaction posting, Clearing file parsing etc.)
- Integration with [Way4 Payment Platform](https://www.openwaygroup.com/way4-payment-platform) via REST, SOAP APIs, SFTP file exchanges
- Digital wallets integration (Apple/Google Pay)
- Integration of Way4 ACS to support 3DS v1/v2 flows
- Integration with HSMs, PKI handling.
- Leading migration of infrastructure from AWS EC2 instances -> AWS ECS Fargate service
- Implementation of a company-wide library in AWS CDK to have a common way of container deployment in Enfuce
- Leading team of 5 developers
- Participation of Enfuce-wide architecture team

**Environment:** Java 17, Spring Boot 2, Spring Cloud Config, Spring MVC, Spring Webflux, Spring Data, Spring Cloud function, resilience4j, Oracle DB, Basic Auth, MTLS, AWS Cloudformation, AWS CDK, AWS SQS/SNS, AWS Lambda, AWS Batch, AWS DynamoDB, AWS S3, AWS API Gateway, Troposhere


#### Gaimin Mining Platform

* Greenfield development of smart mining platform for gamers that allowed mining of 5+ cryptocurrencies, cryptocurrency conversion, cryptotransfers, referral program, etc.

**Customer**: Gaimin

**Project Role:** Team/Tech Leader

**Period:** Feb-2020 - Jan-2021

**Tasks performed:**

- Overall system design that included web app, desktop app & third-party integrations
- Desktop app implementation (Electron + Angular 2+)
- Multiple APIs and third-party integrations (such as Okta, crypto APIs) development (microservice architecture)
- Setting up infrastructure in GCP including running 5+ cryptocurrencies nodes
- Leading team of 5 developers
- Project requirements negotiation with customer
- Project development lifecycle management

**Environment:** Java 11, Spring Boot 2, Spring MVC, Spring Data, MemSQL, OAuth2, JWT, Okta, GKE, GCF, Web3j, Electron, Angular 2+


#### Waffle

*Development of high-performant ISO8583 reactive authorization forwarding service*

**Customer**: Enfuce

**Project Role:** Lead Software Developer

**Period:** Apr-2019 - Now

**Tasks performed:**

- Development of high-performant persistant Netty ISO8583 tcp client
- Implementation of message-passing mechanism via Redis Streams
- Implementation of Redis Cache population with high volumes of data
- Setting up the deployment to AWS with Packer, Ansible, CloudFormation (with Troposhere)
- Development of e2e-tests with TestContainers
- Setting up the gitlab-ci pipeline
- Integration with third party systems (Basic Auth, Mutual TLS)

**Environment:** Java 11, Gradle, Spring Boot 2, Oracle12c, Redis, Redis Streams, Netty, Project Reactor, Lombok, Docker, Docker-compose, TestContainers, AWS, AWS Cloudformation, Troposhere, Packer, Ansible


#### Gaimin Mining Platform

* Greenfield development of smart mining platform for gamers that allowed mining of 5+ cryptocurrencies, cryptocurrency conversion, cryptotransfers, referral program, etc.

**Customer**: Gaimin

**Project Role:** Team/Tech Leader

**Period:** Feb-2020 - Jan-2021

**Tasks performed:**

- Overall system design that included web app, desktop app & third-party integrations
- Desktop app implementation (Electron + Angular 2+)
- Multiple APIs and third-party integrations (such as Okta, crypto APIs) development (microservice architecture)
- Setting up infrastructure in GCP including running 5+ cryptocurrencies nodes
- Leading team of 5 developers
- Project requirements negotiation with customer
- Project development lifecycle management

**Environment:** Java 11, Spring Boot 2, Spring MVC, Spring Data, MemSQL, OAuth2, JWT, Okta, GKE, GCF, Web3j, Electron, Angular 2+


#### PSD2 Open Banking

*Development of PSD2 compliant Open Banking Platform for OP Baltics Customer*

**Customer**: Enfuce

**Project Role:** Software Developer Team Leader

**Period:** Sep-2019 - Jan-2020

**Tasks performed:**

- Implementation of Bulk Payment API (DynamoDB, OAuth2)
- DynamoDB performance improvements.

- Leading team of 3 developers

**Environment:** Java 12, Spring Boot 2, Spring Cloud Config, Spring Boot Admin, Docker, Docker-compose, AWS, AWS Cloudformation, DynamoDB, OAuth2, OIDC, Troposhere, Packer, Ansible


#### PSD2 Hub

*Development of Payment Platform for PSD2 compliant Banks*

**Customer**: Enfuce

**Project Role:** Software Developer Team Leader

**Period:** Jun-2019 - Now

**Tasks performed:**

- Integration of Nordea Bank to platform (OAuth2, Message Signing)
- Integration of Marginalen Bank to platform (OAuth2, Mutual TLS)
- Introduced Spring Boot Admin
- Development of Payment REST API
- Development of Decoupled SCA
- Leading team of 6 developers

**Environment:** Java 12, Gradle, Spring Boot 2, Spring Cloud Config, Spring Boot Admin, Mapstruct, Lombok, Swagger, OpenAPI spec, Docker, Docker-compose, AWS, AWS Cloudformation, DynamoDB, OAuth2, OIDC, Troposhere, Packer, Ansible


### Epam Systems

#### Foundational

**Customer**: Intercontinental Hotel Groups

**Project Role:** Software Developer

**Period:** Jun-2018 - Apr-2019

**Tasks performed:**

- Pipelines were introduced in SMS Market Preferences, Continuous Conversations, Guest Synthesis. All CRM Gold, Bronze & Green apps are on pipelines now.

- All Sonar violations for SMS Market Preferences, Continuous Conversations, Guest Synthesis were addressed. All CRM Gold, Bronze & Green apps have no sonar violations.

- Spring Cloud Config was integrated with Jenkins Pipelines to have instant compatibility of SCC and Application versions for all our apps.

- Integration with QC ALM in Jenkins Pipelines to automatically close QC defects after release build according to Changelog.md records.

- Integration with Fortify Security Scans was implemented in shared Jenkins Pipeline library.

- Separate Sonar Quality Profile that includes Security violations was created to get continuous feedback on security violations.

- Pipelines Performance Tuning: Maven tuning, Git Clone tuning, Get rid of code generation.

**Environment:** Intellij Idea, Maven, Jenkins, SonarQube, Git(Bitbucket), Rally, QC ALM, Jenkins Pipelines, Groovy, Spring Cloud Config, Bash Scripting, Markdown, Fortify Security Scans.


#### Traces Application

*Development of batch process for processing guests events in order to show notifications in integrated Opera PMS system.*

**Customer**: Intercontinental Hotel Groups

**Project Role:** Software Developer

**Period:** Sep-2016 - Dec-2018

**Tasks performed:**

- Integration with ActiveMQ queues.

- Implementation of Throttling Mechanism using Apache Camel to reduce request rate on third-party service.

- Integration with a set of SOAP Services using Apache CXF.

- Design and implementation of REST API (using Spring MVC).

- Performance Analysys & issue investigating using VisualVM.

- BugFixing.

- Direct mailing and oral communication with customer.

**Environment:** Oracle 11G, Intellij Idea, Maven, Jenkins, A (ActiveMQ command-line client), Sonar, VisualVM, JConsole, Chef, Git(Bitbucket), AppDynamics, Rallly, Spring, Hibernate, REST Services and Clients (Spring MVC), SOAP Clients (Apache CXF), JMS (ActiveMQ), JMX, Apache Camel, Swagger, Java 8, Spring Boot


#### Enhanced Member Profile (EMP) & Hotel Comment Admin Tool (HCAT)

*Development of Restful Webservices and UI for managing IHG guests' info and comments.*

**Customer**: Intercontinental Hotel Groups

**Project Role:** Software Developer

**Period:** Feb-2017 - Dec-2019

**Tasks performed:**

- Design and implementation of REST API (using Apache CXF) both for EMP and HCAT.

- Integration with a set of SOAP Services using Apache CXF.

- Development of UI in AngularJS.

- Inroduced Yarn + Webpack stack for UI build.

- Performance Analysys & issue investigating using VisualVM.

- BugFixing.

- Improved Continuous Integration/Delivery process by using Jenkins Pipeline Scripts. Applied results to all existing applications.

- Created Network-Connectivity scripts in Bash language to make it easy to verifyu that all needed firewalls are opened and external services are up before production deployment.

- Direct mailing and oral communication with customer.

**Environment:** Oracle 11G, Intellij Idea, Bash Scripting, Maven, Jenkins, Sonar, TC-Server, VisualVM, Chef, Git(Bitbucket), Chrome Dev Tools, AppDynamics, Rallly, Spring, Hibernate, REST Services and Clients (Apache CXF), SOAP Clients (Apache CXF), JMX, Swagger, Java 8, Groovy, HTML & CSS & Angular JS, Yarn, Webpack, Bash Scripting


#### Spectrum

*Development of API for communication preferences for third-party vendor.*

**Customer**: Intercontinental Hotel Groups

**Project Role:** Software Developer

**Period:** Mar-2017 - Nov-2017

**Tasks performed:**

- Created secured by apikey, documented via Swagger API Gateway using Apigee Platform
- REST API development

**Environment:** Oracle 11G, Apigee, Intellij Idea, Maven, Jenkins, Sonar, Chef, Git(Bitbucket), AppDynamics, Rally, Spring, Hibernate, REST Services and Clients (Spring MVC), SOAP Clients (Apache CXF), Apache Camel, Swagger, Java 8, Spring Boot


#### SVOC (Single View of Customer)

*Development of Web Services and UI for displaying customer related info.*

**Customer**: Intercontinental Hotel Groups

**Project Role:** Software Developer

**Period:** Nov-2015 - Jan-2016

**Tasks performed:**

- Made integration with a set of SOAP Services using Apache CXF.
- Took part in development of REST operations for retieving and searching customer inforamtion.
- Took part in development of UI in AngularJS (mostly consuming rest endpoints data)
- Analyzed the performance using VisualVM.
- Reserched CI Pipelines with Jenkins & Chef.
- BugFixing.
- Direct mailing and oral communication with customer.

**Environment: **Oracle 11G, Maven, Jenkins, Sonar, Intellij Idea, TC-Server, VisualVM, Git (Stash), Rally, Scrum, Spring, Hibernate, REST Services and Clients (Apache CXF), SOAP Clients (Apache CXF), Swagger, Java 8, AngularJS


#### Green Team Apps

**Customer**: Intercontinental Hotel Groups

**Project Role:** Software Developer

**Period:** Aug-2015 - Oct-2015

**Tasks performed:**

- Moved a set of legacy apps to the latest versions of libraries (latest Spring, Hibernate, CXF, Hazelcast)

- Migrated apps to Java 8

- Unified apps structure for Chef Deployment (Migrated from JSW to war files, writing configuration templates for Chef)

- BugFixing.
- Direct mailing and oral communication with customer

**Environment:** Oracle 10G, Intellij Idea, Maven, Jenkins, Sonar, TC-Server, WebSphereMQ Explorer, VisualVM, Chef, Git(Stash), AppDynamics, Rallly, Scrum, Spring, Hibernate, SOAP (Apache CXF), Hazelcast, JMS, Java 8


#### HCM (Hotel Content Management)

*Development of Web Services and UI for managing  hotel informationDevelopment of Web Services and UI for managing  hotel information*

**Customer**: Intercontinental Hotel Groups

**Project Role:** Software Developer

**Period:** Mar-2015 - Jun-2015

**Tasks performed:**

- Developed REST Sevices for showing hotel data on UI

- Developed new and refactored existing AngularJS UI functionality (retrieving data from web-service, page-routing, templating etc.)

- Researched tools for e2e testing of AngularJS apps.
- Created maven+grunt pipeline for running e2e tests
- Created Intellij Idea Plugin for Hot-Swapping resources

**Environment:** Oracle 11G, Mavel, Grunt, Intellij Idea, Git (Stash), Jenkins, Sonar, Chrome Dev Tools, Selenium, Spring, Hibernate, REST Services (Apache CXF), AngularJS, Protractor


