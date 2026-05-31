# Contributing to Deepworks

Thanks for your interest in contributing! These guidelines apply across all [Deepworks](https://github.com/deepworks-net) repositories. Individual repos may add project-specific guidance in their own `CONTRIBUTING.md` — when they do, that takes precedence.

## Code of Conduct

By participating, you agree to uphold our [Code of Conduct](CODE_OF_CONDUCT.md). Please report unacceptable behavior to **support@deepworks.net**.

## How to contribute

1. **Fork** the repository.
2. **Create a feature branch** off the default branch (`git checkout -b feature/short-description`).
3. **Make your changes**, keeping commits focused and atomic.
4. **Test** your changes and ensure existing checks pass.
5. **Open a pull request** against the upstream default branch, filling out the PR template.

## Commit conventions

We use [Conventional Commits](https://www.conventionalcommits.org/). Commit messages should follow:

```
<type>(<optional scope>): <description>
```

Common types: `feat`, `fix`, `docs`, `chore`, `refactor`, `test`, `ci`.

These conventions drive our automated changelog generation and release drafting, so please follow them.

## Versioning

All repositories use [Semantic Versioning](https://semver.org/) (`MAJOR.MINOR.PATCH`). Releases and changelogs are produced automatically from PR labels and conventional commits via our [github.toolkit](https://github.com/deepworks-net/github.toolkit) workflows.

## Pull request expectations

- Keep PRs scoped to a single concern.
- Update documentation (MkDocs/Material) when behavior changes.
- Reference any related issues (e.g. `Closes #123`).
- Apply appropriate labels (`feature`, `fix`, `chore`, `major`/`minor`/`patch`) so release drafting categorizes the change correctly.

## Documentation

Most repositories document with **MkDocs** and the **Material** theme, deployed to GitHub Pages. If your change affects user-facing behavior, update the docs in the same PR.

## Questions

Open a discussion or issue in the relevant repository, or email **support@deepworks.net**.
