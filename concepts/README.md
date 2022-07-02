# Core Concepts of System Design

## High Availability
High Availability (HA) is a property of a system that strives to operate and perform at an agreed level for extended times without intervnention.

Availability is measured in uptime percentage in a given year.

It is achieved by eliminating single points of failure (SPoF) by means of introducing redundancy into the system.

Redundancy can be active or passive, and achieved through load-balancing or failover.

## Load Balancing

Load balancing is a mechanism in which work is distributed across multiple redundant workers within a system, to maintain high availability and responsiveness.

## Microservices

Contrary to Monolithic architecture, Microservices is the architectural pattern in which software is decomposed into small and independent services that communicate over the network through well-defined interfaces.

Microservices are loosely coupled, structured around business capabilities, independently owned, maintained, and deployed.

## CAP Theorem

CAP Theorem states that any distributed system can have at most two of the following three properties: Consistency, Availability, Partition Tolerance.

## Consistent Hashing
Consistent Hashing is a distributed hashing scheme that works independently of the number of servers or objects.

## Domain-Driven Design

Domain-Driven Design (DDD) is the approach of modeling software around input coming from domain experts.

DDD stresses that the evolving model and implementation should be connected, and that a high level of collaboration between engineers and domain experts is cruicial to continually sharpen the model.

Ubiquitous Language is developed collaboratively and is rooted deep into the system to enable both to evolve together.