# Contributing

## Pull requests

Outside contributions are welcome through GitHub pull requests. This repository
is a read-only mirror of the forge, where contributions are gated, reviewed, and
merged. Nothing is merged on GitHub. After a forge merge, the mirror receives the
change and the GitHub pull request is closed with a link to the forge merge.

The importer is not live yet: pull requests are read, but are not being merged
yet. Once it is live, it will bring GitHub pull requests to the forge for review.

## Tests and fixtures

Use invented data in tests and fixtures, such as `acme`, `globex`, and
`service.example`. Do not include real site hosts, organization names, logins,
paths, or other private data.

## Local gate

With the repository's pinned Rust toolchain installed, run from the repository
root (the offline test step requires dependencies to be cached):

```sh
set -e
JERYU_SPLIT_FULL_CHECK=1 ./ops/ci/check.sh
cargo test --offline --workspace
```
