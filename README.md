<!-- BEGIN:AVATAR -->
![Avatar](avatar.jpg)
<!-- END:AVATAR -->

<!-- BEGIN:BADGES -->
[![Build Status](https://github.com/cliffano/release-action/workflows/CI/badge.svg)](https://github.com/cliffano/release-action/actions?query=workflow%3ACI)
[![Security Status](https://snyk.io/test/github/cliffano/release-action/badge.svg)](https://snyk.io/test/github/cliffano/release-action)
<!-- END:BADGES -->

Release GitHub Action
---------------------

GitHub Action for creating a repository release using [RTK](https://github.com/cliffano/rtk).

Usage
-----

Create a major release:

```yaml
jobs:
  build:
    steps:
      - uses: cliffano/release-action@main
        with:
          release_type: 'major'
          push_changes: 'true'
```

The release_type value can be one of `major`, `minor`, or `patch`.

When running tests, set push_changes to false so the action does not push commits or tags to remote repository.

## Colophon

<!-- BEGIN:DEVELOPERS_GUIDE -->
[Developer's Guide](https://cliffano.github.io/developers-guide-github-action.html)
<!-- END:DEVELOPERS_GUIDE -->

<!-- BEGIN:BUILD_REPORTS -->
Build reports:

* [Lint report](https://cliffano.github.io/release-action/lint/yamllint.txt)
* [Test report](https://cliffano.github.io/release-action/test/act.txt)
* [API documentation](https://cliffano.github.io/release-action/doc/action-docs/index.html)

<!-- END:BUILD_REPORTS -->
