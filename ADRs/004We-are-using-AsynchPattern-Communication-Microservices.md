[> Home](../README.md)    [> ADRs](README.md)

---

# Record architecture decisions

Date: 2021-10-21

## Status

Accepted

## Context

Some of the Microservices will communicate each other using [Asynchronous communication Pattern]()
For example
Offering matcher always accept the request using a messages in the input message queue and send the response via output message queue 


## Decision
Some of the Microservices will communicate each other using [Asynchronous communication Pattern]()
For example
Offering matcher always accept the request using a messages in the input message queue and send the response via output message queue


## Consequences

**Positive:**

- Some of the Microservices can take their own time to respond
- We prefer Avalibility 


**Negative:**

- More complex exception handling.

**Risks:**



---

[> Home](../README.md) 