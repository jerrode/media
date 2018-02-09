---------------------------------------------------------------------------------
-------------------------- START THE PITCH --------------------------------------
---------------------------------------------------------------------------------

> Our mission is to bring to everyone the power of microservices.


# Monoliths, Microservices and the Microservice Monolith

Today, there are two application architecture options: monoliths and microservices.
Monoliths are the most popular primarily because logic and code are tightly coupled in a single deployable stack.
Microservices are a collection of specific services that, when orchestrated properly, create a decentralized application with many stacks.

Monoliths are popular for a good reason. They have low devop architecture demands while provide a single point of logic and code for transparent operations.
However, monoliths can be difficult to scale because of language limitations and bottlenecks.
Over time, monoliths accrue technical debt if not maintained properly and refactoring code may require an entire application redesign.
Testing monoliths can be very tricky since logic is deeply embedded.

Microservices are notoriously hard to orchestrate properly which leads to service coupling and high technical debt.
In the worst case, the coupling and poor architecture leads to a Microservice Monolith which has extreme technical debt and vast performance limitations.
However, microservices has been made popular by successful companies like Netflix, Amazon and Google who have nearly mastered orchestration with custom tooling and a team of thousands of engineers.
Microservices are powerful when orchestrated properly. They provide an environment where services can be separately deployed and optimized for the highest performance.


# The Dawn of Microservice Choreography

> An unfamiliar term which has not been defined by a product, yet mentioned in several publications as the future of microservices and application development.

Microservice Choreography is a algorithm of services that communicate in an environment that eliminates container coupling while automating orchestration with transparent data flow.
A service is a language agnostic container, function or algorithm designed to care out a specific operation.

Eliminating orchestration allows developers to focus on application logic instead of architecture. Paving the way for rapid application prototyping to production, building some applications 100x faster.

To achieve Microservice Choreography, we believe, you need domain-specific language for choreography and a platform for orchestration.

The language would be the application logic which choreographs the services.
The platform would be the language execution environment by orchestrating the services and managing security, data and configuration.


# Introducing Asyncy

> `Write stories then code.`

Storyscript is our language for microservice choreography. An expressive, syntax-light language which is highly readable, transparent and functional.
A developer who writes application logic in Storyscript, which we call a Story, can prototype application and architecture quickly and then later fill in the services to complete the application.

Asyncy is the platform for Storyscript execution, service discovery & marketplace, continuous-integration, continuous-delivery and application management.
Our platform uses Kubernetes to automatically orchestrate services in a secure and robust environment.
The entire development workflow is seamless with a rich set of tools including a CLI, CI/CD, IDE Plugins and more.

The new development story is simplified:
1. Write Stories
2. Discovery reusable services or build your own.
3. Test and debug applications with zero configuration.
4. Deploy and scale with no devops overhead.

[Asyncy](https://asyncy.com) is **open source** and **cloud agnostic**.

### Features
1. Open source and cloud agnostic.
1. [Storyscript](http://asyncy.click/storyscript), our domain-specific language, for microservice choreography.
1. Emporium for service discovery and marketplace (i.e., Docker Hub + GitHub Marketplace).
1. Hub for application management, metrics and health (i.e. Heroku).
1. Engine for Storyscript execution.
1. Automated container orchestration using Kubernetes under-the-hood.
1. Simulator for a powerful continuous-integration and continuous-delivery.
1. Atom Plugin for integrated development workflows and machine learning assisted logic.
1. Highly integrated with GitHub for source code management and granular permissions.

> Fun fact. A majority of our application is written in Storyscript. :tada: :rocket:

### Ecosystem and Open Source Contribution

We invite to join our [Slack Community](https://asyncy.click/slack) where the magic happens.
Open source contribution is well received. Yes, we are a for-profit company but our entire tooling is open source.

### Media
Twitter: [@asyncy](https://asyncy.click/twitter)
GitHub: [@asyncy](https://asyncy.click/github)
Slack: [Join](https://asyncy.click/slack)

### Jobs

:unicorn_face: Asyncy is hiring and looking for highly-skilled, influential unicorns that understand the vision and want to join us on this amazing adventure.

Asyncy's HQ is in Amsterdam. Remote Ok.


### Press and Investors

Please inquire at [hello@asyncy.com](mailto:hello@asyncy.com)



---------------------------------------------------------------------------------
---------------------------- END THE PITCH --------------------------------------
---------------------------------------------------------------------------------

> Below are other concepts and topics that we may want to incorporate.


## Our Story

The story behind Asyncy starts with Storyscript, our domain-specific language.
Years back while working on applications for small businesses customers asked for unique, long-running business logic to automate marketing and customer retention, among other business logic.
These stories were written down in a format that the client could read and understand the logic behind the application.
A transparent, syntax-light, language emerged through the common logic patterns that read like a book.
Storyscript was born and paved the way for a new technique of rapidly prototyping applications.
