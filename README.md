# jeryu-cache

JeryuCache policy, CAS, receipts, and adversarial poisoning tests.

This repository was seeded from Jeryu source commit `cbecf7caa0e932c76a341b2521e66e911233860d` by
`ops/split/materialize.py`. It is part of the seven-repo Jeryu split family and keeps source
paths stable where practical so ownership remains auditable.

## Owned Cargo Packages

- `crates/jeryu-cache-core`
- `crates/jeryu-cache-service`
- `crates/jeryu-cache-cli`
- `crates/jeryu-cache-adversary`
- `crates/jeryu-cache`

## Source Coverage

- `crates/jeryu-cache-core/**`
- `crates/jeryu-cache-service/**`
- `crates/jeryu-cache-cli/**`
- `crates/jeryu-cache-adversary/**`
- `crates/jeryu-cache/**`
- `tests/cache_poisoning_matrix.sh`
- `fixtures/cache-poisoning/**`
- `config/jeryu-cache-policy.toml`
- `policies/cache-laws.toml`
- `examples/cache-key-material.json`

## Local Commands

- `just fast`
- `just check`
- `just score`
- `just security`
- `just artifact-support`
