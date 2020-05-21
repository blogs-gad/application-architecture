# What is an application architecture?

An application architecture describes the patterns and techniques used to design and build an application. The architecture gives you a roadmap and best practices to follow when building an application, so that you end up with a well-structured app.

Software design patterns can help you to build an application. A pattern describes a repeatable solution to a problem.

Patterns can be linked together to create more generic application architectures. Instead of completely creating the architecture yourself, you can use existing design patterns, which also ensure that things will work the way they’re supposed to.

As part of an application architecture, there will be both front-end and back-end services. Front-end development is concerned with the user experience of the app, while back-end development focuses on providing access to the data, services, and other existing systems that make the app work.

The architecture is a starting point or roadmap for building an application, but you’ll need to make implementation choices not captured in an architecture. For example, a first step is to choose a programming language in which to write the application.

There are many programming languages used for software development. Certain languages may be used to build certain types of applications, such as Swift for mobile apps or JavaScript for front-end development. 

JavaScript used with HTML and CSS is currently 1 of the more popular programming languages for web application development. 

Other popular programming languages include Ruby, Python, Swift, TypeScript, Java, PHP, and SQL, among others. The language used when building an application will depend on the type of application, available development resources, and the requirements. 

Historically, applications were written as a single unit of code, where the components all share the same resources and memory space. This style of architecture is referred to as a monolith.

Modern application architectures are more often loosely coupled, using microservices and [application programming interfaces \(APIs\)](https://www.redhat.com/en/topics/api/what-are-application-programming-interfaces) to connect services, which provide the foundation for cloud-native applications. 

Cloud-native development is a way to speed up how you build new applications, optimize existing ones, and provide a consistent development and automated management experience across private, public, and hybrid clouds.

## Choosing an application architecture 

When deciding which application architecture to use for a new application, or when evaluating your current architecture, start by determining your strategic goals.

Then you can design the architecture that supports your goals, instead of choosing an architecture first and trying to make an application fit within that structure. 

Consider how frequently you want to release updates to meet customer or operational needs, as well as what functionality is required by either business objectives or development needs. 

The ability to rapidly provide new services and new functionality to customers is one of the key competitive differentiators a company can offer. And faster development lets businesses release new features more often, and roll out updates as soon as a vulnerability is discovered.

There are many different types of application architectures, but the most prominent today, based on the relationships between the services are: monoliths and N-tier architecture \(tightly coupled\), microservices \(decoupled\), and event-driven architecture and service-oriented architecture \(loosely coupled\).

## Layered or N-tier architecture

A layered or N-tier architecture is a traditional architecture often used to build on-premise and enterprise apps, and is frequently associated with legacy apps.

In a layered architecture, there are several layers or tiers, often 3, but there can be more, that make up the application, each with their own responsibility. 

Layers help to manage dependencies and perform logical functions. In a layered architecture, the layers are arranged horizontally, so they are only able to call into a layer below. 

A layer can either only call into the layer immediately below it, or it can call into any of the layers below it. 

## Monolithic architecture 

A monolith, another architecture type associated with legacy systems, is a single application stack that contains all functionality within that 1 application. This is tightly coupled, both in the interaction between the services and how they are developed and delivered. 

Updating or scaling a single aspect of a monolithic application has implications for the entire application and its underlying infrastructure. 

A single change to the application code requires the whole application to be re-released. Because of this, updates and new releases typically can only occur once or twice per year, and may only include general maintenance instead of new features. 

In contrast, more modern architectures try to break out services by functionality or business capabilities to provide more agility.

## Microservices architecture

[Microservices](https://www.redhat.com/en/topics/microservices) are both an architecture and an approach to writing software. With microservices, apps are broken down into their smallest components, independent from each other. Each of these components, or processes, is a microservice.

Microservices are distributed and loosely coupled, so they don’t impact one another. This has benefits for both dynamic scalability and fault tolerance: individual services can be scaled as needed without requiring heavy infrastructure or can failover without impacting other services.

The goal of using a microservices architecture is to deliver quality software faster. You can develop multiple microservices concurrently. And because services are deployed independently, you don’t have to rebuild or redeploy the entire app when changes are made. 

This leads to more developers working on their individual services at the same time, instead of updating the whole application, resulting in less time spent in development and the ability to release new features more often.

Along with APIs and [DevOps](https://www.redhat.com/en/topics/devops) teams, containerized microservices are the foundation for cloud-native applications.

## Event-driven architecture 

With an event-driven system, the capture, communication, processing, and persistence of events are the core structure of the solution. This differs from a traditional request-driven model.

An event is any significant occurrence or change in state for system hardware or software. The source of an event can be from internal or external inputs.

[Event-driven architecture](https://www.redhat.com/en/topics/integration/what-is-event-driven-architecture) enables minimal coupling, which makes it a good option for modern, distributed application architectures.

Event-driven architecture is made up of event producers and event consumers. An event producer detects or senses an event and represents the event as a message. It does not know the consumer of the event, or the outcome of an event.

After an event has been detected, it is transmitted from the event producer to the event consumers through event channels, where an event processing platform processes the event asynchronously.

An event driven architecture may be based on either a pub/sub model or an event stream model.

The pub/sub model is based on subscriptions to an event stream. With this model, after an event occurs, or is published, it is sent to subscribers that need to be informed.

This differs from an event streaming model where event consumers don’t subscribe to an event stream. Instead, they can read from any part of the stream and can join the stream at any time.

Events are captured as they occur from event sources such as Internet of Things \(IoT\) devices, applications, and networks, allowing event producers and event consumers to share status and response information in real time.

## Service-oriented architecture

The service-oriented architecture \(SOA\) is a well-established style of software design, that is similar to the microservices architecture style. 

SOA structures apps into discrete, reusable services that communicate through an enterprise service bus \(ESB\). 

In this architecture, individual services, each organized around a specific business process, adhere to a communication protocol \(like [SOAP](https://middlewareblog.redhat.com/2017/08/30/integrating-soap-based-web-services-into-red-hat-3scale-api-management/), ActiveMQ, or Apache Thrift\) and expose themselves through the platform of an ESB. Taken together, this suite of services, integrated through an ESB is used by a front-end application to provide value to a business or customer.

## How Red Hat can help with application development

Red Hat’s solutions help you improve business agility by breaking down your monolithic applications into microservices, managing them, orchestrating them, and handling the data they create to help your teams deliver quality solutions to your customers faster.  

As you create new business applications, you’re able to do it with the future in mind, building easily scalable and agile [cloud-native apps](https://www.redhat.com/en/topics/cloud-native-apps)—and integrating them with the rest of your business—from the beginning.

There’s no need to totally overhaul your existing systems to get meaningful benefits. Through open source, open standards, and our years of experience, we can help you find a microservices-based solution that fits your organization.

Through our open source portfolio, including [Red Hat® Enterprise Linux®](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux), [Red Hat OpenShift®](https://www.redhat.com/en/technologies/cloud-computing/openshift), and [Red Hat Middleware](https://www.redhat.com/en/products/middleware), we think Red Hat is uniquely positioned to partner with companies who must change to compete in fast-paced, software-driven markets.





