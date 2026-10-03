# Codex Cloud Workspace

This repository is the source-controlled workspace for Codex Cloud tasks.

## Use in Codex Cloud

1. In Codex, choose **Work in > Cloud** and create an environment.
2. Select this repository when prompted.
3. Let Codex inspect and test the environment, then publish it.

Codex Cloud keeps each task isolated. Commit work that should be retained in this repository.

## Repository conventions

- Keep project instructions in `AGENTS.md`.
- Never commit secrets, credentials, or local environment files.
- Add a dependency manifest and documented verification command when the first project is added.
