# ADR 1 : Domain based Services

## Status  

Accepted

## Rationale 

All services we introduce must be based on the business domains and subdomains. This will create logic grouping of our microservices and ensure that the microservices that is getting built are only focusing on implementing functionality for that domain only.

## Decision
ADR Proposed, pending approval.

## Consequences  
Positive:
+ Loosely couple microservices and group them into "clusters" focused on a particular domain
+ Services designed around domain concepts tend to be more maintainable because changes to the domain can be localized to the affected services. This reduces the risk of unintended side effects and makes maintenance more predictable.

Negative:
+ Domains need to be defined early and properly and if not done properly can have adverse impact the implementation of the microservices

