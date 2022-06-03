[> Home](../README.md)    [> ADRs](README.md)

---

# Record architecture decisions

Date: 2021-10-21

## Status

Accepted

## Context

We have decide to use Domain Driven Design to Decompose the System into multiple Bounded Context.
The context map can be found [here](..//Context%20Map.pdf)

## Decision

We have decompised the system using the Domain Driven design. We have identified following Bounded Contex
- Career Management
- Candidate onBoarding
- Mentor Onbaoding
- Community Management
- Non-Profit onboarding
- Analytics
- publication 


## Consequences

**Positive:**

- Easy to evolve  the Architecture for new requirement 
- Clear seperation of concern for each bounded context 
- Every Bounded Context may have one or more aggregate
-  Aggregate may have same name but have different meaning different Bounded Context (Context is king) 
- Seperation of responsibility based on the business capability
- Seperate Domain services for Business Capability
- We have combines the Back end for Front End Service with Domain Services to power the User Interface

**Negative:**

- Transaction management may be difficult when the business process trigered 

**Risks:**

- Someone not familiar with ADRs may not know where to find them or that they exist.

**Bonus Features:**

- Easy to Imeplement Analytics capability because Analytics bounded context is downstream to most of the other bounded context
---

[> Home](../README.md)    [> ADRs](README.md)