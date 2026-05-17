# ADR-003: Use ORM for database interactions

Date: ~2019
Status: Accepted
Category: data
Confidence: 95%

## Context

Database interactions were becoming complex and prone to errors. The decision to use an ORM for database interactions was made to address this issue, with constraints including consistency and simplicity.

## Decision

The chosen approach was to use the existing Django ORM to simplify database interactions and improve consistency.

## Consequences

### Positive

- Improved database interaction consistency
- Reduced errors

### Negative

- Additional complexity in ORM configuration

## Evidence trail

- `conduit/apps/authentication/models.py`
