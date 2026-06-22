# banana

This repository is an experimental placeholder. It has no committed product
implementation, production service, package, API, or deploy path yet.

## Lifecycle

- State: `incubating`
- Layer: `research`
- Machine manifest: [`.doctrine/project.json`](./.doctrine/project.json)

## Goals

- Preserve a doctrine-compatible entry point for future experimental work.
- Require any future implementation to declare its concrete project goal,
  boundary, public surfaces, validation, and delivery proof before production
  use.

## Non-Goals

- Do not treat this placeholder as a production product.
- Do not add project-specific hacks for another repository.
- Do not create public API, deployment, billing, or commercial commitments
  without a project-specific ADR or manifest update.

## Boundary

This repository currently owns only its initialization metadata and experimental
placeholder identity. It does not own production behavior, shared platform
capabilities, customer-facing workflows, billing, deployment, or public API
behavior until those facts are explicitly declared here and in
`.doctrine/project.json`.

## Public Surfaces

- Documentation: `AGENTS.md`, `PROJECT.md`, `.doctrine/project.json`

## Delivery

No CI or deployment is defined. Production proof is not applicable until the
repository contains implementation or release artifacts.

## Commercial Direction

Not applicable. No pricing, packaging, paid entitlement, or commercial
experiment is declared for this placeholder.
