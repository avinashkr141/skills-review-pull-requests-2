# Contributing Guide

Thanks for your interest in contributing to this repository.

## Before You Start

- Be respectful and constructive in discussions and reviews.
- Check open issues and pull requests to avoid duplicate work.
- Read the security policy in [SECURITY.md](SECURITY.md) before reporting vulnerabilities.

## Development Workflow

1. Fork the repository (if you are not a direct collaborator).
2. Create a feature branch from `main`.
3. Make focused changes with clear commit messages.
4. Push your branch and open a pull request.
5. Address review feedback and update your branch.

## Branch Naming

Use short, descriptive names:

- `feat/add-game-reset`
- `fix/cell-click-bug`
- `docs/update-security-policy`

## Commit Message Style

Use clear commit messages that describe intent:

- `feat: add reset button for tic tac toe board`
- `fix: prevent duplicate click on occupied cell`
- `docs: add codeowners and contributing guide`

## Pull Request Requirements

Please include:

- A clear summary of what changed and why.
- Any related issue number (if applicable).
- Screenshots or short notes for UI changes.
- Confirmation that your change was tested locally.

Keep pull requests small and focused. Smaller PRs are reviewed faster and with better feedback.

## Review and Ownership

This repository uses code ownership rules in [.github/CODEOWNERS](.github/CODEOWNERS).

- Opening a PR automatically requests reviews from matching code owners.
- If branch protection is enabled with required code-owner review, PRs cannot merge until required approvals are complete.

## Testing Checklist

Before opening a PR:

- Open `index.html` and verify the page loads without errors.
- Verify your change works on desktop and mobile viewport sizes.
- Confirm no sensitive information (keys, tokens, credentials) is added.

## Security Reporting

Do not open public issues for vulnerabilities.

Use the process described in [SECURITY.md](SECURITY.md), including private vulnerability reporting.

## Documentation Updates

If behavior changes, update relevant docs in the same PR:

- [README.md](README.md)
- [SECURITY.md](SECURITY.md)
- [CONTRIBUTING.md](CONTRIBUTING.md)

## Questions

If something is unclear, open a discussion in the PR and ask for clarification. Clear communication helps maintainers review faster.
