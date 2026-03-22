# github-account-scanner detection sample

This repository is an experiment-only repository for `github-account-scanner`.

It exists to verify that the scanner can detect:

- a newly created repository
- a newly published GitHub release

## Status

- This repository is temporary.
- It is not a production project.
- Its releases are intentionally small and may contain documentation-only changes.

## Why it exists

This repository gives `github-account-scanner` a safe target for repeatable end-to-end tests:

- create a repository
- publish a release
- confirm that the scanner detects the event
- confirm that Discord notification flow works as expected

## Contents

- `README.md`: explains why this repository exists and why it should be treated as test-only
- `sample-config.json`: tiny sample payload for release verification
- `CHANGELOG.md`: compact notes for the next test release
