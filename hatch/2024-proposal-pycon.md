<div align="center">

<img src="https://raw.githubusercontent.com/pypa/hatch/master/docs/assets/images/logo.svg" alt="Hatch logo" width="500" role="img">

| Proposer                     | Year | Outcome  | Video |
| ---------------------------- | ---- | -------- | ----- |
| [Ofek Lev](https://ofek.dev) | 2024 | accepted | TBA   |

</div>

-----

**Table of Contents**

- [Title](#title)
- [Category](#category)
- [Duration](#duration)
- [Description](#description)
- [Audience](#audience)
- [Level](#level)
- [Objectives](#objectives)
- [Outline](#outline)
- [Additional Notes](#additional-notes)
  - [Speaking experience](#speaking-experience)
  - [Accessibility](#accessibility)

## Title

Hatch: The only tool you need

## Category

Packaging/tooling

## Duration

30 minutes

## Description

While other language ecosystems have a streamlined workflow that involves a single tool like Rust's [Cargo](https://github.com/rust-lang/cargo) and JavaScript's [npm](https://github.com/npm/cli), maintaining Python projects has historically involved learning and using an ever-growing set of tools:

- packaging: `distutils`, `setuptools`, `flit`
- dependency management: `pip`, `pip-tools`, `poetry`
- Python management: `pyenv`,  Homebrew, Windows store
- environments: `virtualenv`, `tox`, `nox`
- versioning: `pbr`, `setuptools_scm`, `bump2version`, `versioneer`
- builds: `pip`, `build`
- publishing: `twine`
- ...

This talk explains how [Hatch](https://github.com/pypa/hatch) can be that unified tool for Python.

## Audience

Programmers at any level that wish to simplify their development experience.

## Level

Any

## Objectives

Attendees will learn how to manage the entire lifecycle of a project with Hatch from creation to publishing.

## Outline

1. Intro (3 minutes)
   - brief history
   - why rewrite
   - status/current users
2. Project setup (2 minutes)
   - installation
   - porting setuptools-based projects
   - creating new projects, with options
3. Python management (1 minute)
4. Packaging (6 minutes)
   - briefly show `pyproject.toml` metadata
   - build targets
   - metadata hook plugins
   - file inclusion
     - defaults
     - benefits vs setuptools config
     - VCS support
   - dev mode
   - build hook plugins
5. Dependencies (2 minutes)
   - commands
   - auto-sync
   - workspaces, monorepos
6. Environments (8 minutes)
   - basic options
   - philosophical difference between `tox` & `nox`
   - scripts
   - context formatting
   - matrices
   - overrides
   - environment plugins
7. Static analysis via Ruff (2 minutes)
8. Testing via pytest (2 minutes)
9. Versioning (2 minutes)
   - source plugins
   - bumping
10. Publishing (1 minute)
11. Future (1 minute)
    - [extension modules](https://github.com/ofek/extensionlib)
    - [lock files](https://discuss.python.org/t/17690)

## Additional Notes

### Speaking experience

I have not spoken at any software conferences.

### Accessibility

I'm in an electric wheelchair.
