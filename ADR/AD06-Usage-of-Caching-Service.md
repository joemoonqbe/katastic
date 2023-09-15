# ADR 06: Using Caching Service

## Status  

Proposed

## Rationale 
A high performance Caching service must be used utilised where applicable to allow for faster access to commonly requested data. 
This reduces the amount of expensive "read" operations on databases used across the enterprise. 
"Cache-Aside" is the most common pattern that should be utilised and caching should be done closer to experience layer.

## Decision
ADR Proposed, pending approval.

## Consequences  
Positive:
+ Greatly reduce data load and improve response time and user experience

Negative:
+ Can add complexity to APIs and services which need to query cache or data store
+ Need to carefully think through TTL of each cache and revise them over time
+ Need to carefully consider what data can be cached and what cannot be to avoid misuse

