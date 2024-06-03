<img align="right" src="https://raw.github.com/cliffano/release-action/master/avatar.jpg" alt="Avatar"/>

[![Build Status](https://github.com/cliffano/release-action/workflows/CI/badge.svg)](https://github.com/cliffano/release-action/actions?query=workflow%3ACI)
<br/>

Release GitHub Action
---------------------

GitHub Action for creating a repository release using RTK.

Usage
-----

Create a major release:

    jobs:
      build:
        steps:
          - uses: cliffano/release-action@latest
            with:
              type: 'major'
