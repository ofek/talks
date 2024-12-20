<div align="center">

| Proposer                     | Year | Outcome | Video |
| ---------------------------- | ---- | ------- | ----- |
| [Ofek Lev](https://ofek.dev) | 2025 | pending | N/A   |

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

PyApp: Distributing Python applications

## Category

Packaging/tooling

## Duration

30 minutes

## Description

A perpetual hardship when distributing Python applications has been that Python itself is a dependency. You, and more importantly your users, need to in some way get Python before your software can even be used. The recommended way to go about that is platform-dependent and even differs based on your target audience.

[PyApp](https://github.com/ofek/pyapp) is a runtime installer for Python projects written in Rust. Apps are distributed as standalone executables as users have come to expect and bootstrapping occurs upon the first invocation.

In this talk, I will demonstrate how easy this makes shipping Python applications.

## Audience

Programmers at any level that wish to distribute their Python applications as standalone executables.

## Level

Any

## Objectives

Attendees will learn how to use PyApp to distribute their Python applications.

## Outline

1. Intro (3 minutes)
     - When to use
     - Libraries vs applications
     - When not to use
2. Prior art (3 minutes)
     - PyInstaller
     - cx_Freeze
     - Pex / Shiv
     - Nuitka
     - PyOxidizer
     - scie-jump / ptex
3. Example (2 min)
     - Show terminal of developer and user
     - Install Rust
     - Fetch PyApp code base
     - Configure
     - Build & distribute
4. Runtime behavior (2 minutes)
     - Bootstrapping
     - Caching
     - Execution
5. Configuration (6 minutes)
     - Project
     - Python distribution
     - Installation/bootstrapping behavior
     - CLI
6. Management commands (2 minutes)
     - Updates
     - Restoration
     - Direct Python access
7. Platform installers (4 minutes)
     - Why bother
     - Windows MSI
     - macOS PKG
     - Linux
8. Future (3 minutes)
     - Builder CLI
     - Improve editable installs
     - Official guidance on platform installers

## Additional Notes

### Speaking experience

I spoke at PyCon 2024.

### Accessibility

I'm in an electric wheelchair.
