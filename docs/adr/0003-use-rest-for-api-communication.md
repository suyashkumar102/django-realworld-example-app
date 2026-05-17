# ADR-003: Use REST for API communication

Date: ~2019
Status: Accepted
Category: communication
Confidence: 100%

## Context

The project requires a standardized API communication protocol. The decision to use REST for API communication was influenced by simplicity and scale constraints. Using REST for API communication simplifies the implementation and improves scalability.

## Decision

The decision to use REST for API communication was made due to its ability to provide a standardized and scalable API communication protocol. REST is widely adopted and has a simple implementation, making it a suitable choice for the project.

## Consequences

### Positive

- Standardized and scalable API communication protocol
- Simple implementation using REST

### Negative

- Potential limitations in handling complex API requests

## Alternatives Considered

- **GraphQL for API communication**: Not chosen due to the simplicity and widespread adoption of REST

## Evidence trail

- `conduit/apps/authentication/urls.py`
