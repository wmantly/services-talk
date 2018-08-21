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

## Networking

## Deploying

A seriver is deployable unit 

## Vocabulary and Abriavation

* **Severless**
* **SOA**

## Resources

[1 Wiki: Microservicers](https://en.wikipedia.org/wiki/Microservices)

[2 Wiki: Service-Oriented Architecture](https://en.wikipedia.org/wiki/Service-oriented_architecture)

[3 Meduim: ASW Local tools](https://medium.com/@takezoe/how-to-develop-aws-based-application-in-the-local-environment-3e36eb705adf)

[4 Cloudingmine: Idempotence Services](http://cloudingmine.com/idempotence-what-is-it-and-why-should-i-care/)

[5 Meduim: OOD Analysis](https://medium.com/omarelgabrys-blog/object-oriented-analysis-and-design-design-principles-part-6-b78e2b9da023)

[6 MSDN: Understanding Service-Oriented Architecture](https://msdn.microsoft.com/en-us/library/aa480021.aspx)



## Books

[Practical Object-Oriented Design in Ruby](https://www.poodr.com/)
