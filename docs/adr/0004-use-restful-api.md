# ADR-004: Use RESTful API

Date: ~2019
Status: Accepted
Category: communication
Confidence: 90%

## Context

API endpoints were not following a standard architecture. The decision to use a RESTful API was made to address this issue, with constraints including simplicity and scale.

## Decision

The chosen approach was to define URL patterns for RESTful API endpoints. This approach was chosen due to its simplicity and scalability benefits.

## Consequences

### Positive

- Improved simplicity
- Increased scalability

### Negative

- Added complexity to the API endpoints

## Evidence trail

- `conduit/apps/authentication/urls.py`
