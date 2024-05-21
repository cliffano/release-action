<img align="right" src="https://raw.github.com/cliffano/studio-release-action/master/avatar.jpg" alt="Avatar"/>

[![Build Status](https://github.com/cliffano/studio-release-action/workflows/CI/badge.svg)](https://github.com/cliffano/studio-release-action/actions?query=workflow%3ACI)
<br/>

Studio Release GitHub Action
----------------------------

GitHub Action for creating a repository release using RTK.

Usage
-----

Create a major release:

    jobs:
      build:
        steps:
          - uses: cliffano/studio-release-action@latest
            with:
              type: 'major'
