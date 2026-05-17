# ADR-001: Use JWT for authentication

Date: ~2019
Status: Accepted
Category: auth
Confidence: 95%

## Context

The project requires a secure and stateless authentication mechanism to handle user sessions. The decision to use JWT for authentication was influenced by performance and simplicity constraints. The use of an existing library (jwt) for authentication simplifies the implementation and improves performance.

## Decision

The decision to use JWT for authentication was made due to its ability to provide a secure and stateless authentication mechanism. JWT is widely adopted and has a simple implementation, making it a suitable choice for the project.

## Consequences

### Positive

- Secure and stateless authentication mechanism
- Simple implementation using an existing library

### Negative

- Potential security vulnerabilities if not implemented correctly

## Alternatives Considered

- **Session-based authentication**: Not chosen due to the need for a stateless authentication mechanism

## Evidence trail

- `conduit/apps/authentication/backends.py`
- `conduit/apps/authentication/models.py`
