# QubitWorks Documentation

Shared documentation, engineering guidelines, and reusable practices for projects maintained by the QubitWorks organization.

## What's here

This repository contains documentation intended to be shared across QubitWorks projects and repositories.

The documentation is organized by topic:

- **Engineering** — Shared development environment recommendations, Git workflow, and engineering practices.
- **Guides** — Reusable technical guides and procedures that may be useful across projects.

Project-specific documentation should generally live alongside its relevant source code or in a dedicated repository. Hardware- and testbed-specific documentation should be maintained separately from organization-wide guidelines.

## Getting started

Start with the engineering guidelines:

- [Development Environment](engineering/development-environment.md) — Development environment setup and recommendations.
- [Git Workflow](engineering/git-workflow.md) — Shared Git contribution workflow for QubitWorks repositories.

Additional technical guides are being developed and reviewed:

- [Yocto Build Guide — PR #1](https://github.com/qubitworks-lab/documents/pull/1)
- [Ubuntu Overlay and Driver Guide — PR #5](https://github.com/qubitworks-lab/documents/pull/5)

Guides may have different prerequisites, tested configurations, and limitations. Check the relevant documentation before following a procedure.

## Documentation principles

- Keep organization-wide guidelines in this repository.
- Keep project-specific implementation details with their respective projects.
- Avoid duplicating shared documentation across repositories; link to the canonical document instead.
- Document tested configurations, prerequisites, and known limitations where applicable.
- Keep confidential information out of public documentation, logs, and screenshots. Passwords, tokens, and private keys must never be committed to Git repositories, including private ones.

## Questions and contributions

If something is unclear, outdated, or broken, please [open an issue](https://github.com/qubitworks-lab/documents/issues).

For documentation changes:

- Small corrections and focused pull requests are welcome.
- Discuss larger changes in an issue first to avoid duplicated work.
- For technical procedures, describe what was tested and what remains unverified.
- If a decision is made outside GitHub, summarize it in the relevant issue or pull request.
