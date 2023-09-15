# ADR 06 : 

## Status  

Proposed

## Rationale 
A high performance Caching service must be used where applicable to allow access to commonly requested data. This reduces amoung of expensive "read" on persistant data storage used across the enterprise.

## Decision
ADR Proposed, pending approval.

## Consequences  
Positive:
+ Greatly reduce data load and improve response time and user experience

Negative:
+ Can add complexity to APIs and services which need to query cache or data store
+ Need to carefully think through TTL of each cache and revise them over time 

