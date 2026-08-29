# Contributing at Gryph Labs

This repository contains organization-wide GitHub profile material. Product repositories may add project-specific contribution requirements.

## Repository changes

1. Create a focused branch for the change.
2. Keep the change limited to one clear intent.
3. Open a pull request against the repository's default branch.
4. Explain what changed and why.
5. Run any repository-specific validation before requesting review.
6. Resolve review findings before merge.

Do not commit secrets, credentials, tokens, private keys, or production customer data.

## Commit and branch guidance

Use descriptive branch names such as:

- `feature/<jira-key>-short-description`
- `fix/<jira-key>-short-description`
- `docs/<jira-key>-short-description`
- `chore/<short-description>` when no Jira item is appropriate

Prefer commits that describe the completed change rather than the editing process.

## Source-of-truth boundaries

- Jira owns executable work and acceptance criteria.
- Confluence owns durable architecture, governance, and decisions.
- GitHub owns source, tests, repository configuration, PR history, and CI evidence.

Link to canonical information instead of copying large bodies of documentation into multiple systems.
