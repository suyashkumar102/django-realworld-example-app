# ADR-005: Use unit testing bias

Date: ~2019
Status: Accepted
Category: testing
Confidence: 80%

## Context

Code was not being thoroughly tested, leading to bugs and errors. The decision to use unit testing was made to address this issue, with constraints including team size and simplicity.

## Decision

The chosen approach was to use the existing Django test framework and define API views. This approach was chosen due to its simplicity and team size benefits.

## Consequences

### Positive

- Improved test coverage
- Increased simplicity

### Negative

- Added complexity to the testing process

## Evidence trail

- `conduit/apps/authentication/views.py`
