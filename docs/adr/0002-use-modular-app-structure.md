# ADR-002: Use modular app structure

Date: ~2019
Status: Accepted
Category: structure
Confidence: 90%

## Context

Monolithic app structure was becoming difficult to maintain and scale. The decision to use a modular app structure was made to address this issue, with constraints including scale and simplicity.

## Decision

The chosen approach was to define an app config class and register it with Django, using a modular app structure to organize code and reduce complexity.

## Consequences

### Positive

- Improved maintainability
- Easier scaling

### Negative

- Additional complexity in app configuration

## Evidence trail

- `conduit/apps/authentication/__init__.py`
