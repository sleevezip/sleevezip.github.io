---
layout: post
title: API First Approach
categories: [api, design]
tags: [api, design, OpenAPI]
description: Importance of API First approach
---
# Importance of API First approach

An API-First approach means developing with APIs that are consistent and reusable. This can be done by using an API description language to establish the contract for how the APIs are supposed to be designed and behave. By taking an API-First approach more time can be spent on planning and collaboration with the stakeholders, for providing feedback on the design of an API before any code is written. This can be called design-first approach too, whereas more time is taken to flesh out the design of the API. Previously an application would be planned, built, tested and only after that there would be time for feedback. While in a design-first approach there is more time taken in the design step so there is time feedback and this feedback is incorporated within the build process.

![](https://raw.githubusercontent.com/sleevezip/sleevezip.github.io/master/assets/media/Code%20first%20vs%20Design%20First.png)

The API-First approach builds the API first and builds the applications( web or mobile) on top of that API. This way, it will allow parallel development by all teams without the need to wait for changes to be released by one team or another. All teams can start their work using the first mocked APIs. Once the API is ready, all teams can switch to the production or staging API. This saves development time and prevents teams of having to wait for one another and having idle development time.

## API-First vs. Code first
Swagger can be integrated with REST APIs in below ways:

**A top-down approach ** – First API specification and then, code generation </br>
**A bottom-up approach** – First code and then Swagger integration. This is quite familiar and most useful when there is already an existing REST APIs built in and Swagger documentation needs to be integrated.
### Advantages in Contract first (API-First):
- Loose-coupling between contract and implementation is possible
- Possible to create reusable schema definition
- Handling of versioning easily
- Higher performance
- Maintenance is easier
### Disadvantages in Contract last (code first):
- Changes in the service will affect the service contract
- Implementation changes will change the contract which will affect the clients
- The performance of web service is affected by this method
- Less re-usability, because of lack of flexibility and extensibility,
- Does not cover a wide range of consumers, because service is for a specific application.
