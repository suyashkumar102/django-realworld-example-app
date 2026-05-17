# ADR-002: Use Django app structure

Date: early project (~2012)
Status: Accepted
Category: structure
Confidence: 100%

## Context

The project requires a structured and modular project organization. The decision to use Django's app structure was influenced by simplicity and team size constraints. Using Django's built-in app structure simplifies the implementation and improves maintainability.

## Decision

The decision to use Django's app structure was made due to its ability to provide a structured and modular project organization. Django's app structure is widely adopted and has a simple implementation, making it a suitable choice for the project.

## Consequences

### Positive

- Structured and modular project organization
- Simple implementation using Django's built-in app structure

### Negative

- Limited flexibility in project organization

## Alternatives Considered

- **Custom project structure**: Not chosen due to the simplicity and maintainability of Django's app structure

## Evidence trail

- `conduit/apps/authentication/__init__.py`
