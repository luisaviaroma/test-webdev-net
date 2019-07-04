# test-webdev-net
Code Test for Web Developer .NET

## Abstract
The candidate should develop a simple RESTful+JSON .NET/.NET Core web application that implements a CRUD API for managing a phonebook.  
Data should be persisted across webapp restarts and access to them must be resilient to concurrency.  
Webapp should also be resilient to malformed requests.  

## Required Technologies
- .NET Framework >= 4.7 or dotnetcore >= 2
- NuGET
- sqlite

## Suggested Frameworks
- Autofac
- xUnit
- Anything that can be useful for testing and documenting the API(s)

## How to deliver the artifact
Fork this repository to your github account and issue a pull request when ready to merge.

## Key evaluation points
- Code quality
- Code runnability
- Documentation
- Testability
- Platform independency: any client should be able to call the API, regardless of how the API is implemented internally. This requires using standard protocols, and having a mechanism whereby the client and the web service can agree on the format of the data to exchange. 
- Service evolution: the web API should be able to evolve and add functionality independently from client applications. As the API evolves, existing client applications should continue to function without modification. All functionality should be discoverable so that client applications can fully use it


