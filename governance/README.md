# Governance

This directory defines how canonical status and decisions are recorded without making unsupported claims authoritative.

## Public status framework

Use these labels on every material claim:

- **VERIFIED** — supported by authoritative evidence
- **AVAILABLE** — demonstrable in a controlled current environment
- **CONFIGURABLE** — components exist but require deployment or integration
- **REPORTED** — stated by a source but not independently confirmed
- **INFERENCE** — reasoned from evidence
- **PROPOSAL** — future design, price, feature, or action
- **OPEN** — unresolved
- **CONFLICT** — credible sources disagree

## Capability entry template

| ID | Component | Capability | Status | Public evidence | Verification date |
|---|---|---|---|---|---|
| CAP-XXX |  |  | PROPOSAL |  |  |

Do not publish confidential commercial rights, private ownership arrangements, security details, customer information, or deployment gates in this public repository.

## Decision entry template

| ID | Date | Public decision | Status | Supersedes |
|---|---|---|---|---|
| DR-XXX | YYYY-MM-DD |  | PROPOSED |  |

Sensitive decision records should remain in an access-controlled system. Public entries should state only what other users and tools need in order to work accurately.

## Merge rule

A document stored in the repository is not canonical solely because it exists. Canonical status must be stated by the README, governance policy, or an approved public decision entry.
