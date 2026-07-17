# Invalid lockfile pull-request fixture

This repository isolates the pull-request UX for a YAML-valid but
schema-invalid GitHub Actions lockfile.

The default branch contains the `pull_request` workflow and a valid lockfile.
A fixture pull request changes `dependencies` from a mapping to a list.
