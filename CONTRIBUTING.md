# Contributing to Laucked

Thanks for your interest in contributing. This organization publishes offensive security methodology tooling, and we welcome improvements from the community.

Before you start, please read this guide and our [Security Policy](./SECURITY.md).

## Ground rules

- **Responsible use.** Our tools are built for authorized security testing only. Do not use them, or contribute features designed for use, against systems you do not own or have explicit written permission to test.
- **No leaked material.** We do not accept content derived from copyrighted course material, certification exams, or any source you are not permitted to redistribute. Original work only.
- **Be respectful.** Assume good faith, keep discussions technical, and help newcomers.

## Ways to contribute

- **Report a bug.** Open an issue with clear reproduction steps and your environment details.
- **Request a feature.** Open an issue describing the use case and the problem it solves, not just the solution.
- **Improve docs.** Typos, clarifications, and better examples are always welcome.
- **Submit code.** See the pull request workflow below.

## Reporting issues

Search existing issues first to avoid duplicates. When opening a new one, include:

- A clear, descriptive title
- What you expected to happen and what actually happened
- Steps to reproduce
- Version, OS, and any relevant configuration

For anything that looks like a security vulnerability, do not open a public issue. Follow our [Security Policy](./SECURITY.md) instead.

## Pull request workflow

1. Fork the repository and create a branch from `main` (`feature/short-description` or `fix/short-description`).
2. Make focused commits with clear messages.
3. Add or update tests and documentation where relevant.
4. Run the project's linter and tests locally before pushing.
5. Open a pull request describing what changed and why, and link any related issue.

We aim to review pull requests within a few business days. Smaller, focused changes are reviewed and merged faster than large ones.

## Coding standards

- Follow the conventions already present in the repository.
- Keep functions and modules focused and documented.
- Avoid adding dependencies unless they earn their place.
- Write commit messages in the imperative mood (for example, `Add GraphQL introspection check`).

## Licensing

By contributing, you agree that your contributions are licensed under the same license as the repository you are contributing to. If a repository has no license file, ask before submitting substantial work.

## Questions

Open a discussion or issue, or reach us at contact@laucked.com.
