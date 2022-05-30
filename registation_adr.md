# Onboarding Service

## Status - Proposed

## Context

Building one onboarding service for non-profits and users vs separate

## Decision

We should build separate onboarding service for non-profits and users as they are different domains. 
They would have separate scalability concerns. 
Fault in onboarding service will not intersect with fault in non-profit service hence higher fault tolerance

## Consequences

