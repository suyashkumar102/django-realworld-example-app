# ADR-004: Use Django ORM for database interactions

Date: ~2019
Status: Accepted
Category: data
Confidence: 100%

## Context

The project requires an efficient and scalable database interaction mechanism. The decision to use Django ORM for database interactions was influenced by performance and simplicity constraints. Using Django ORM for database interactions simplifies the implementation and improves scalability.

## Decision

The decision to use Django ORM for database interactions was made due to its ability to provide an efficient and scalable database interaction mechanism. Django ORM is widely adopted and has a simple implementation, making it a suitable choice for the project.

## Consequences

### Positive

- Efficient and scalable database interaction mechanism
- Simple implementation using Django ORM

### Negative

- Potential limitations in handling complex database queries

## Alternatives Considered

- **Raw SQL for database interactions**: Not chosen due to the simplicity and maintainability of Django ORM

## Evidence trail

- `conduit/apps/authentication/models.py`
