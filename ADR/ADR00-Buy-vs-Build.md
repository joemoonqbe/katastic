# ADR 0 : Buy VS Build Components

-- If team do not want to invest time and quick wins

## Status  
Proposed

## Rationale 


 

## Decision   
We will use the Microservices architecture to model the Hey Blue! system

## Consequences  
Postitive:
+ Gives us a roadmap to steer the evolution of the system
+ Allows us to separate heavily used components into their own processes to allow them to scale
+ Clearly identifies the Domain model and partitioning of the system.  

Negative:  
+ Data and code duplication
+ Difficult to execute quickly if we strictly adhere to the architecture and develop each microservice from scratch