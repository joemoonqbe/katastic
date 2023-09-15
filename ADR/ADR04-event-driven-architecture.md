# ADR 04 : Event Driven Architecture

## Status  
Proposed

## Rationale 

All actions need to be published as platform wide events even if there are no immediate consumer for those events. This will achieve horizontal scalability of the system as whole and future proof it to great extent. A common high performance enterprise-wide message broker will be required for this purpose.


## Decision
ADR Proposed, pending approval.

## Consequences  
Positive:
+ Future use cases for events need to tap into message broker and start consuming the messages
+ Allows for real time processing of data
+ Allows for loosely coupled systems and microservices to reduce interdependencies making it easier to extend individual systems without affecting entire systems

Negative:
+ Given the volume of information going through the message broker, this system must be highly available and may require expensive underlying computing resources
+ Event ordering may not be possible and this need to be considered where event ordering is important
+ Event loss can be problem where consumers are unable to process the event due to any technical issue
+ Event flood can occur when sudden surge in events can flood consumer services

