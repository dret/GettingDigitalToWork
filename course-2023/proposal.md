# API Design and Management: From Start to Scale

This course covers API design and management and also looks at questions of how to scale that practice from initial APIs to a larger set of APIs. The focus is both on externally facing APIs (for partners or the public) as well as for internally facing ones (for private users).

What distinguishes this course from others is a more holistic viewpoint. We start not by asking what to do when you design an API. Instead, we start by reflecting on why we are doing his, because this motivation to invest in APIs should be driving force determining the entire API practice. This is an intensive 3-day course which will provide you with a solid foundation to start with API design and development and then scale it up in your organization, while at the same time making sure that you never lose sight of the objectives underlying the API work.


## Day 1: API Product Design

### Morning: API Foundations

#### APIs (DL)

- What is an API and why APIs?
- Private, partner, and public APIs
- API Styles and API Technologies
-- HTTP, HTTP/REST, GraphQL, Messages, Events, ...
- API Description Languages

After having a short round of introductions (name, occupation, goals for this training), we start with laying out our motivations in this training: Why are APIs important and what are our goals for this training (laying foundations for API developers). Next are the foundations: First, we need to define our concepts: What is an API, what is an API client, what an API provider, what are operations, what are messages? We also discuss the differences between syncronous and async (incl event) APIs. After we have clarified these technology-agnostic concepts, we will have a look at what technologies (HTTP, HTTP/REST, GraphQL, MQTT, SOAP, Kafka, ...) are avaiable today and in the past.  In the last part we move over to API descriptions. Why are interfaces/contracts important and what options are there to document an API?

#### REST (EW)

- RESTful APIs: HTTP as an Application Protocol

### Afternoon: Building a Good API

#### APIs as Products (EW)

- API Business Models
- API Products and API First

#### Lifecycle & Versioning (DL)

Usually the context of APIs is integration of different systems which are developed by different teams and have different lifecycles and deployments. We want to decouple the systems and thus need to plan API evolution beforehand in order to not break compatibility and thus functionality in the overall system. This requires the awareness of what changes influence compatibility and an evolution strategy which allows to make incompatible changes if required by business or regulatory requirements. We will discuss different stretegies like deprecation and two-in-production for handling different scenarios.

- API Lifecycle
- API Versioning
- Compatibility

## Day 2: Managing the API Lifecycle

### Morning: The API Design Process

#### ADDR (EW)

- Aligning Business Goals
- Defining the Ubiquitous Language
- Designing the API
- Refining the API Product
- API Linting
- API Mocking

#### Patterns? (DL)

Patterns are distilled and documented experience collected from many projects. There are many pattern collections regarding API design out there and we will present some and will showcase some patterns in more detail. 
A pattern describes a context and a problem and a possible, abstract solution which resolves different forces in a positive or negative way.
Especially important to API designers are Enterprise Integration patterns and API Design Patterns. We will dive into the correlation, context representation, and pagination patterns.

- EIP (Correlation)
- MAP (...)

### Afternoon: API Development

#### Tools I (beide: Tools suchen)

- Postman Collections and Workspaces
- stop light
- OpenAPI Generator
- APIs and SDKs
- API Documentation
- API Security

#### Tools II (später)

- Lab Tools

## Day 3: Scaling the API Practice

### Morning: APIs and Automation

#### API Governance, Programs and Platforms (EW)

- Governance
-- API Guidelines
- Center of Excellence vs. Center for Enablement

#### Build/Platform (DL)

DevOps and CI/CD (and efficient software development in general) require automation to deliver higher-quality solutions in a shorter time. This means that API contract verification, code generation, and deployments need to be automated. In this block we will discuss how to structure your Maven projects as a low-entry, low-cost solution and show what Maven plugins can be used to help developers.

In the next step we will have a look at changes to the development environment if an API platform is established. What artefacts become globally managed and how can API gateways help the whole organization and the projects itself and which drawbacks do they have.

- Projektstrukturen
- Integration in Builds
- Linter
- Templates
- API Gateways to enforce development process

### Afternoon: "Life Hacking", bring it all together, example project (später nach Tools)
