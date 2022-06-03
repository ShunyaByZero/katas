[> Home](../README.md) 
---

# Record architecture decisions

Date: 2022-27-05

## Status

Accepted

## Context

We will be using the [Backend for FrontEnd Pattern](https://philcalcado.com/2015/09/18/the_back_end_for_front_end_pattern_bff.html) for User Interfcae to access the back end Services

## Decision
We will be using Backend for FrontEnd Pattern for accessing the Backens services from the UI.

## Consequences

**Positive:**

- Less network calls between the UI and Domain services.
- BFF service will be seperate from domain services ideally but here we have decided to combine.
- The UI availability is linked to uptime of BFF service not all the domain services  

**Negative:**

- BFF will have extra complexity of synching the data across the domain services.

**Risks:**

- Someone not familiar with ADRs may not know where to find them or that they exist.

---

[> Home](../README.md)    