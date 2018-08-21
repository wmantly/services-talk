# Services

I was asked to do a presentation on `Mirco Services`.

## Topics

* **Benefits** why should an organization use microservices?
* **Challenges** what should an organization keep in mind when going to microservices, particularly the “hidden challenges” from the “unknown unknowns”.
* **Development** methodologies, procedures, and processes
* **Production** operations – methods, procedures, and processes
* **Tooling** what sorts of tools exist and what sorts of tools does a microservices-focused organization need to know about
* **Staffing** are there different staffing needs (size, skills, organization) for microservices vs monolithic?

## Questions

Why should an organization use microservices?

Does *serverless* change the calculus?


## Developing

> *SOA is not just an architecture of services seen from a technology perspective, but the policies, practices, and frameworks by which we ensure the right services are provided and consumed.* -- MSDN[6]

> *...what is generally agreed amongst practitioners of SOA is that it is by no means a free lunch. Like many good practices in software engineering, it is an investment that will require extra planning, development and testing.* -- ANDREW CROSIO[8]

Document exiting services

  Exiting API sush as Data Access and REST services need to documented, clearly stating intent, access controll and opporations. New services need to be clearly ducumented in the same way prior to being put into production. Self ducumenting API framworks such as Slate is a good way to start the documentaion.
  
API documentation is a public interface, just like any other object or class. Infact many of the Object Oriented Desing princables apply to the application layer;

* **KISS** Keep It Simple, Stupid
* **DRY** Don’t Repeat Yourself
* **SOLID**
  * **S**  Single Responsibility Principle. An object (or service) should have one and only one responsibility.
  * **O** Open/Closed Principle
  * **L** Liskov Substitution Principle.
  * **I** I nterface Segregation Principle. Interfaces (Services and their API's) should be specific rather than doing many and different things.
  * **D** Dependency Inversion Principle. 

Versioned API and Interfaces. Start with Version 0 for beta and move to version 1 when its ready for production. Plane for breaking changes and change the version with many breaking changes. Try not to move to version to often. Planing is inportant.

Containers/emulated envoiments

standeres

templates

## Services
> *A well formed service provides us with a unit of management that relates to business usage. Enforced separation of the service provision provides us with basis for understanding the life cycle costs of a service and how it is used in the business.* -- MSDN[6]

> SOA involves the deployment of services, which are units of logic that run in a network. A service has the following characteristics:
> * It handles a business process such as calculating an insurance quote or distributing email; handles a technical task such as accessing a database; or provides business data and the technical details to construct a graphical interface.
> * It can access another service. With the appropriate runtime technology, it can access a traditional program and respond to different kinds of requesters, such as web applications.
> * It is relatively independent of other software. Changes to a requester require few or no changes to the service. Changes to the internal logic of a service require few or no changes to the requester. The relative independence of the service and other software is called loose coupling*

> -- IBM[7]

## Networking

## Deploying

A seriver is deployable unit 

## Vocabulary and Abriavation

* **Severless**
* **SOA**
* **Monolithic Application** self-contained, and independent from other computing applications. A single-tiered application in which the UI and data access code are combined into a single program from a single platform.

## Resources

[1 Wiki: Microservicers](https://en.wikipedia.org/wiki/Microservices)

[2 Wiki: Service-Oriented Architecture](https://en.wikipedia.org/wiki/Service-oriented_architecture)

[3 Meduim: ASW Local tools](https://medium.com/@takezoe/how-to-develop-aws-based-application-in-the-local-environment-3e36eb705adf)

[4 Cloudingmine: Idempotence Services](http://cloudingmine.com/idempotence-what-is-it-and-why-should-i-care/)

[5 Meduim: OOD Analysis](https://medium.com/omarelgabrys-blog/object-oriented-analysis-and-design-design-principles-part-6-b78e2b9da023)

[6 MSDN: Understanding Service-Oriented Architecture](https://msdn.microsoft.com/en-us/library/aa480021.aspx)

[7 IBM: Service-Oriented Architecture](https://www.ibm.com/support/knowledgecenter/en/SSMQ79_9.5.1/com.ibm.egl.pg.doc/topics/pegl_serv_overview.html)

[8 toptal: AWS Lambda for Ultimate Service Oriented Architecture](https://www.toptal.com/aws/service-oriented-architecture-aws-lambda)

[9 AWS: Application Achitecture Center](https://aws.amazon.com/architecture/)

[10 AWS: Microservices on AWS White Paper PDF](https://docs.aws.amazon.com/aws-technical-content/latest/microservices-on-aws/microservices-on-aws.pdf?icmpid=link_from_whitepapers_page)

## Books

[Practical Object-Oriented Design in Ruby](https://www.poodr.com/)
