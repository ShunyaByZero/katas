[> Home](../README.md) 

---

# Record architecture decisions

Date: 2021-10-21

## Status

Accepted

## Context

We have decided to use External Authentication system such as OKTA to do the User Authentication using a Oath2.0 flow and OpenIDConnect (OIDC) Standard.

## Decision

Instead of building our own Authentication system for users we have decided external Third party Authentication system such as OKTA. We have taken this decision to focus on core business domains



## Consequences

**Positive:**

- Put more focus on the core domain.


**Negative:**

- Some learning curve to udnerstand on how to register the user etc.

**Risks:**

- We have crerated a dependency on the external System. Our Avalibility is now dependent on this Third party Authenticator


---

[> Home](../README.md)    