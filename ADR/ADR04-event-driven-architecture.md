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

Negative:
+ Given the volume of information going through the message broker, this system must be highly available and may require expensive underlying computing resources

