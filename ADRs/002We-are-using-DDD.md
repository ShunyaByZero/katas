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

- Easy to access evolve  the Architecture for new requirement 
- Clear seperation of concern of bounded context 
- Seperation of responsibility based on the business capability
- Seperate Domain services for Business Capability
- We have combines the Back end for Front End Service with Domain Services to power the User Interface

**Negative:**

- Transaction management may be difficult when the business process trigered 

**Risks:**

- Someone not familiar with ADRs may not know where to find them or that they exist.

**Bonus Features:**

- This format will be something we use in other projects to improve architecture decisions governance!

---

[> Home](../README.md)    [> ADRs](README.md)