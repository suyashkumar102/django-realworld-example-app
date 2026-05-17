# ADR-001: Use JWT for authentication

Date: ~2019
Status: Accepted
Category: auth
Confidence: 95%

## Context

Unauthenticated requests were creating security vulnerabilities and unverified access to sensitive data. The decision to use JWT for authentication was made to address this issue, with constraints including consistency and simplicity.

## Decision

The chosen approach was to use the existing jwt library and define a JWTAuthentication class to handle authentication. This approach was chosen due to its simplicity and consistency with existing authentication solutions.

## Consequences

### Positive

- Improved security
- Stateless authentication

### Negative

- Additional complexity in token management

## Alternatives Considered

- **Session-based authentication**: JWT is more suitable for stateless authentication

## Archaeology

> The following evidence suggests alternatives were considered before this decision was made.

- **Session-based authentication** — rejected: JWT is more suitable for stateless authentication
  > Evidence (`commented_out`): `conduit/apps/authentication/backends.py`

## Evidence trail

- `conduit/apps/authentication/backends.py`
