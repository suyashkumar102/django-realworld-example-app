# ADR-005: Use Django database backend

Date: ~2019
Status: Accepted
Category: infrastructure
Confidence: 100%

## Context

The project requires a reliable and maintainable database backend. The decision to use Django database backend was influenced by consistency and simplicity constraints. Using Django database backend simplifies the implementation and improves maintainability.

## Decision

The decision to use Django database backend was made due to its ability to provide a reliable and maintainable database backend. Django database backend is widely adopted and has a simple implementation, making it a suitable choice for the project.

## Consequences

### Positive

- Reliable and maintainable database backend
- Simple implementation using Django database backend

### Negative

- Potential limitations in handling complex database operations

## Alternatives Considered

- **Custom database backend**: Not chosen due to the simplicity and maintainability of Django database backend

## Evidence trail

- `conduit/apps/authentication/migrations/0001_initial.py`
