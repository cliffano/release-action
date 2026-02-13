<img align="right" src="https://raw.github.com/cliffano/release-action/main/avatar.jpg" alt="Avatar"/>

[![Build Status](https://github.com/cliffano/release-action/workflows/CI/badge.svg)](https://github.com/cliffano/release-action/actions?query=workflow%3ACI)
[![Security Status](https://snyk.io/test/github/cliffano/release-action/badge.svg)](https://snyk.io/test/github/cliffano/release-action)
<br/>

Release GitHub Action
---------------------

GitHub Action for creating a repository release using [RTK](https://github.com/cliffano/rtk).

Usage
-----

Create a major release:

    jobs:
      build:
        steps:
          - uses: cliffano/release-action@main
            with:
              type: 'major'

The type value can be one of `major`, `minor`, or `patch`.
