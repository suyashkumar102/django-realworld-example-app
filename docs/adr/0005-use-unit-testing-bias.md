# ADR-005: Use unit testing bias

Date: ~2019
Status: Accepted
Category: testing
Confidence: 80%

## Context

Code was not being thoroughly tested, leading to bugs and errors. The decision to use unit testing was made to address this issue, with constraints including simplicity and team size.

## Decision

The chosen approach was to use unit testing to improve code quality and reduce debugging time, importing Django's test framework and defining API views.

## Consequences

### Positive

- Improved code quality
- Reduced debugging time

### Negative

- Additional complexity in test configuration

## Evidence trail

- `conduit/apps/authentication/views.py`
