# ADR 04 : Using Technologies that are not restricted to a Platform

## Status  
Proposed

## Rationale 

Any technology we introduce for frontend, middleware or backend service must utilise technology that allow for it to be platform agnostic. For example, Using React Native will reduce the build effort for both Iphone and Android and allows for "build once and deploy everywhere".


## Decision
ADR Proposed, pending approval.

## Consequences  
Positive:
+ Reduces build effort by not writing building native application for each platform
+ Commonly available skills the market
+ Helps avoid vendor or platform lock-in

Negative:
+ Often such tools like ReactNative are not as performant as building on platform native tools (Swift for iOS) as they may not allow for low level access to underlying platform.
