# ADR-002: Use modular app structure

Date: early project (~2012)
Status: Accepted
Category: structure
Confidence: 90%

## Context

Monolithic app structure was becoming difficult to maintain and scale. The decision to use a modular app structure was made to address this issue, with constraints including scale and simplicity.

## Decision

The chosen approach was to define an app config class and register it with Django, using a modular app structure to organize code. This approach was chosen due to its simplicity and scalability benefits.

## Consequences

### Positive

- Improved maintainability
- Increased scalability

### Negative

- Added complexity to the app structure

## Evidence trail

- `conduit/apps/authentication/__init__.py`
