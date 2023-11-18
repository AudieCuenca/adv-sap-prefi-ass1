## Assignment in Advanced Systems Integration & Architecture

1. Define Service Oriented Architecture(SOA).

- Service Oriented Architecture is a method for developing and setting up software systems where several separate services
 work together to accomplish certain tasks.Every service is made up of the code and data connections needed to carry out a particular
 business task, think of it as a team where everyone performs a different job and works together to complete tasks quickly.
 It facilitates the seamless operation of many software components.


2. List and discuss the characteristics of SOA.

Standardized service contract – Standardized service contract is an exact contract describing the ways 
of communication between various software services, allowing their collaboration by following identical guidelines.


Loose coupling - Loose coupling describes a software architecture where different services or software 
components are mostly separate from one another. As a result, the client application shouldn't be destroyed 
or become inoperable if a service contain fails repeatedly. allowing simpler adjustments and flexibility without disturbing the system.


Abstraction – Abstraction involves limiting the amount of information that is presented about a service and keeping the details 
of how it operates hidden, so that other components may interact with it more easily without having to know all its complex inner workings.


Service reusability - Service reusability minimizes duplication of work and time wasted developing the same program again for 
different applications, logic is separated into services. This allows for easy application and adaptation, which promotes efficiency.


Autonomy – Autonomy It oversees the logic they include. The service should have total control over the code it includes as 
it is fully aware of the capabilities it provides. granting each service, the autonomy to run its own operations, 
improving the system's overall flexibility and scalability.


Statelessness – Statelessness is Remaining stateless that implies that services shouldn't keep information secret across states. 
Because each request is self-contained and independent of the past, this architecture facilitates scalability and streamlines communication.


Discoverability - Discoverability is the ability to locate and comprehend the services that are offered within
 a system without the need for prior experience.


Composability - Composability refers to the simplicity that software services can be merged or organized to 
produce new, complex functionality. To put it briefly, it divides complicated issues into smaller ones.


Interoperability - Interoperability use guidelines that enable different users to access the service. This enables different software 
systems or services to communicate and collaborate with ease, guaranteeing that they can understand and apply each other's
 functions and data without any problems.



3. Define Microservices.
- Microservices is a kind of software architecture that organizes an application as a collection of services. The program is 
divided into manageable, independent, and tiny services that collaborate to offer overall functionality. Developing, scaling, and maintaining 
complicated programs is made simpler with microservices, which are like constructing a digital system out of tiny, specialized building pieces, 
each doing a particular task.


4. List and discuss the benefits of using Microservices.
Scalability - is a great benefit of microservices including quicker code updates and scalability and the capacity for separate components to 
grow independently, allowing for effective resource use based on requirements. This makes it simpler to add, delete, update, and expand each cloud microservice. 

Flexibility - Is also considered to be a benefit since microservice applications may be developed in any language, allowing developers to work on 
and deploy each one independently. This allows for quicker development cycles and easier adaptation to changing needs. 

Reusability - in Microservices has the additional benefit of being reusable across other projects or applications. 
This allows applications to be shared within an organization, fostering development efficiency and consistency.



5. List and discuss the similarities and differences of SOA and Microservices.
SIMILARITIES
•	Modularity - Architecture's use of the same module in many configurations allows for a wide range of designs. This is known as modularity. 
Microservices and Service-Oriented Architecture (SOA) are two modular techniques that divide systems into more manageable, smaller components.
•	Loose Coupling - is a method of linking the parts of a system, network, or software program so that those parts may work together. 
Both designs promote loose coupling, which enables separate services or parts to function separately without being overly dependent on one another.

DIFFERENCES 
•	Communication - Microservices encourage protocol variety, decentralized communication, and asynchronous interactions, 
allowing for greater flexibility in service communication options, whereas Service-Oriented Architectures (SOA) often rely on standardized protocols and centralized communication with synchronous interactions.

•	Interoperability - While Microservices provides for a variety of technology stacks, allowing for more flexible but various 
approaches to interoperability, SOA stresses established protocols for universal interoperability.

•	Service granularity - While Microservices focuses on smaller, single-purpose services with finer granularity, 
offering more flexibility and independence, SOA often comprises bigger, more complete services.

