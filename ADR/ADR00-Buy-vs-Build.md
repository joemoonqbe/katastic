# ADR 0 : Buy VS Build Components

## Status  
Accepted

## Rationale 
As a startup, the decision often comes down to our specific needs, the skills of our team, and our long-term vision.
As we need to move quickly and want to focus on our core value proposition, buying is usually the best choice for non-ip services.
For our specialized needs, or for the components which area core part of our unique offering, building it ourself is often warranted.

## Decision   
Weigh these considerations carefully, ideally with input from technical, business, and financial team members, to make the most informed decision, we have decied to build the Booking aggrgator services, 
Insight analytics and Communication services which are generic ones will be pay-as-you go saas model. 

## Consequences  
Postitive:
+ Get teh MVP out quickly.
+ Gives us a roadmap to steer the evolution of the system, in a phased manner. 
+ Allows us to separate startup, IP services and heavily used generic components into their own processes to allow them to scale 
+ Clearly identifies the critical services

Negative:  
+ Integration and dependency with External Saas providers which will be critical for the services.
+ Difficult to execute quickly if we need more advanced features
+ Scaling cost and vendor lock in for services