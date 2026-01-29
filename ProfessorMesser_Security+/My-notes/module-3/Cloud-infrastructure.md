#### 🎓 Professor Messer Study Notes

## Cloud Infrastructure - CompTIA Security+ SY0-701 - 3.1

[Link to video](https://youtu.be/8qpQ8Q6xxiU?si=5opKWl1zzOWJKn8g)

### Notes

The cloud can run many different types of services:
- IaaS (Infrastructure as a service)
- PaaS (Program as a service)
- SaaS (Software as a service)

If you are working with a public cloud provider, they will tend to give you a matrix of responsibilities. This shows who’s responsible for what.

These responsibilities may vary per provider.

Hybrid cloud means the use of multiple clouds for your organisation. These can be private or public clouds

Most cloud provider software will not communicate together so you will have to manually set each cloud service.

Each provider typically writes different logs too with different terminology making it difficult to combine.

When data is being shared from one cloud to another there is a risk of data leak as it is traversing the internet.

It’s common that when you upload an application for example to a cloud service that you may want to also use a third party firewall to protect the application. For this, it’s good practice to have a Vendor Risk management policy.

It’s also important that you include a third-party impact for incident response. 

When setting up cloud based services, you need to write out your infrastructure (web-servers, database, etc.) as code to define the infrastructure.

A server less architecture is as it sounds. A server less setup. This can be used for FaaS (function as a service). These functions preform task for the applications. When we need to preform the function, we can call to the serverless system.

The developer still needs to crate the logic and what event may trigger the function. But these are much cheaper. 

All security is covered by the cloud.

Monolithic application means that one big app does everything. 

Microservices are things like API’s (Application programming interfaces). These allow us to add third party functions and data to our application. 
