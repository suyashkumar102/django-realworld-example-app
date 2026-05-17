# ADR-003: Use ORM for database interactions

Date: ~2015
Status: Accepted
Category: data
Confidence: 95%

## Context

Database interactions were becoming complex and prone to errors. The decision to use an ORM for database interactions was made to address this issue, with constraints including consistency and simplicity.

## Decision

The chosen approach was to use the existing Django ORM models and define a custom User model. This approach was chosen due to its simplicity and consistency benefits.

## Consequences

### Positive

- Improved consistency
- Increased simplicity

### Negative

- Added complexity to the database interactions

## Evidence trail

- `conduit/apps/authentication/models.py`
