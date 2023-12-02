## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- The Service-Oriented Architecture (SOA) architectural style organizes software systems as a collection of divided, loosely connected services. These services are designed to perform specific company operations and communicate with each other through a network. By breaking up large, complex systems into smaller, easier-to-manage services.

2. List and discuss the characteristics of SOA.
- Loose Coupling. They don't rely too heavily on the internal activities of other services; instead, they interact using standard interfaces. This adaptability makes it simpler to integrate and modify services without creating major disruptions to the system as a whole.

Interoperability. Because SOA encourages interoperability, services can cooperate independently of the technology, programming language, or platform on which they are constructed. This is similar to various gadgets having communication capabilities even though they are manufactured by different companies or run different operating systems.

Scalability. Because of its modular design, SOA is scalable. As needed, you can change the services without changing the system as a whole. Systems can readily adjust to new needs and handle a variety of workloads because to their scalability.

Reusability. An SOA's services are made to be reusable in many processes or applications. This means that a service can be used in multiple situations after it is built, which shortens the time it takes to develop and encourages consistency throughout different divisions within a company.

3. Define Microservices.
- Building software programs as a group of small and independent, and freely linked services is known as microservices architecture. Every service can act as a stand-alone, standalone process and is concentrated on carrying out a particular business function.

4. List and discuss the benefits of using Microservices.
- Scalability. Services may expand independently because of microservices. Certain services can be scaled without compromising the application as a whole when demand for them rises. Better management of changing workloads and effective resource usage are ensured by this scalability.

Agility and Faster Development. Individual microservices can be developed and deployed independently by groups. The distribution of updates, new features, and enhancements can happen more quickly due to this parallel development strategy. Because specialized, smaller teams may work on particular services without having to wait for the complete program to be developed or updated, it improves agility.

Flexibility and Modularity. Because microservices are modular, adding, changing, or replacing features is simpler. Because they may be developed, tested, and implemented independently, they offer more versatility in terms of responding to changing requirements or advances in technology.

Improved Fault Isolation. The entire application may not be affected if a microservice fails. The overall resilience and dependability of the system are increased by separating failures to individual services, which facilitates problem identification and resolution.

5. List and discuss the similarities and differences of SOA and Microservices.
- Similarities: 
Service-Based: Both SOA and Microservices are service-based architectures. They break down applications into smaller, manageable units (services) that focus on specific functionalities or business processes.

Loose Coupling: Both architectures aim for loose coupling between services. They emphasize the independence of services, allowing them to operate and evolve separately while communicating through well-defined interfaces.

Scalability: Both SOA and Microservices architectures enable scalability. They allow for individual services or components to be scaled independently to meet changing demands without affecting the entire system.

- Differences:
Scope and Granularity: Larger, more generalized services that can include a variety of activities and possibly extend several business areas are part of Service-Oriented Architectures (SOA). At the same time, microservices are more lightweight, narrowly focused, and frequently exclusive to a single business function or capability.

Technology and Implementation: No particular technology or architecture is required by SOA. In order to meet company needs, it focuses on merging current services. On the other hand, Microservices are constructed from the ground up as separate components, each with its own technology stack, and frequently use modern technology and cloud-native approaches.

Organizational Impact: Because of its enterprise-wide focus, SOA may need more centered administration and oversight, which might require greater departmental interaction. Because they are decentralized, microservices are frequently associated with smaller, independent teams that have more control over certain services.

6. Define Web Services.
- A web service is similar to an online software utility that communicates with other programs over an established messaging protocol. It is a flexible stand-alone program that is easily accessible online for use. These technologies enable information sharing across applications, regardless of the fact that they are written in different languages or operate on other computer systems. It resembles the communication between various components of a computer somewhat, except it takes place over the internet between different applications.

7. List and discuss the benefits of using Web Services.
Exposing the Existing Function on the network- An internet-based collection of instructions is similar to a web service. By submitting particular requests over the internet, other programs can make advantage of these instructions. It's a means of allowing other programs, no matter how far away, know what your software is capable of.

Interoperability - Web services enable information sharing and communication between many programs. They allow apps developed using different technologies to function together. They enable smooth app collaboration no matter the technology platforms on which they are developed.

Standardized Protocol - Web services conform to a set of established rules for communication. These regulations address several levels of information transmission and description. Businesses gain much from the traditional approach of collaboration, including increased choice, reduced costs due to competition, and higher-quality products.

Low Cost Communication - Web services can be accessed over your home internet since they rely on a simple and affordable protocol called SOAP over HTTP. This is much less expensive than specialized techniques like B2B or EDI. Web services can also be used with other dependable systems, such as FTP, providing you with other options for how to use them.

8. List and discuss the characteristics of Web Services.
XML-Based - XML is used by web services to handle data. This is important since it releases them from being restricted to a particular platform, operating system, or network. This makes web services highly accessible across a wide range of systems.


Loosely Coupled -  You are not forced to utilize an online service permanently. You will not experience any issues using the web service even if it changes its functionality. If one side of a system with tight connections changes, the other side must adjust as well. However, you're not as set in stone when using online services, so it's easier to adjust when situations change.

Coarse-Grained - When web services are described as "coarse-grained," it means that they manage large-scale activities or tasks as opposed to complex, small-scale ones. Rather than handling separate, individual duties, they manage broader, more expansive operations involving multiple phases or procedures.

Ability to be Synchronous or Asynchronous - In synchronous settings, the client waits for the service to complete before proceeding. Asynchronous operations, on the other hand, allow the customer to resume their other tasks after requesting the service. It can then return later to see the outcome. The capacity to operate independently is essential for loosening the connections between systems.

Supports Remote Procedure Calls (RPCs) - Web services allow users to make remote requests using an XML query language. These queries are similar to being a query or providing guidance to an intangible being. After that, this object returns the required data or action outcomes.

Supports Document Exchange -  XML is great because it can represent complicated objects like complete books or business requests, in addition to simple items like addresses. This is how web services distribute these papers with ease, facilitating collaboration across several industries.

9. List and discuss the distinct roles in Web Services Architecture.
Provider - The web service is created by the provider and made available to client applications upon request. 

Requestor - The client application that needs to get in touch with a web service is known as a requestor. Any language-based application that searches for functionality through a web service can be used as the client application.

Broker - All that the broker is is the program that gives users access to the UDDI. The client application can find the web service thanks to the UDDI.

Publish - In order to make the web service available to clients, a provider uses the broker's publish interface to notify the broker (service registry) of its existence. 

Find - When looking for a published web service, the requestor interacts with the broker. 

Bind - The requestor is able to bind, or invoke, the web service using the details about it that it got from the broker (service registry).

10. List and discuss the Web Services Components.
SOAP - It's a common method via which web services are able to communicate with one another online. To enable applications written in different languages or operating on different platforms to comprehend and interact with one other's data, SOAP offers a structure and guidelines for message formatting and transmission over networks.

WSDL - Web Services Description Language is referred to as WSDL. It serves as an explanation of how to use web services, much like a user manual. It explains a web service's parameters, data types, and operations. It is written in XML. Consider it as a user guide for a web service.

UDDI - Universal Description, Discovery, and Integration is referred to as UDDI. It's a common language for publishing, identifying, and describing web services. By enabling companies to register their web services, it acts as a kind of yellow pages for businesses, making it simpler for other companies to locate and utilize them.

SOAP Web Services - Web services that use the SOAP protocol to transfer data between apps are known as SOAP Web Services, or Simple Object Access Protocol Web Services. An XML-based protocol called SOAP establishes a common message format for web services to communicate with one another. This facilitates communication between apps operating on various platforms and written in different programming languages.

