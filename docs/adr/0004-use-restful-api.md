# ADR-004: Use RESTful API

Date: ~2019
Status: Accepted
Category: communication
Confidence: 90%

## Context

API endpoints were not following a standardized interface. The decision to use a RESTful API was made to address this issue, with constraints including simplicity and scale.

## Decision

The chosen approach was to define URL patterns for RESTful API endpoints, using a RESTful API to simplify API interactions and improve scalability.

## Consequences

### Positive

- Improved API consistency
- Easier scaling

### Negative

- Additional complexity in API endpoint configuration

## Evidence trail

- `conduit/apps/authentication/urls.py`
