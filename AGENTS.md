AGENTS.md

Project Overview

This repository contains an existing Flask REST API for a mini-shop application.

The primary development goal is to implement Redis-based caching according to the project assignment while preserving the existing architecture and functionality.

Treat this as an existing codebase, not a greenfield project.

Technology Stack

Known project technologies:

- Python 3.12+
- Flask
- SQLAlchemy
- PostgreSQL
- uv for dependency management
- Docker Compose for local development
- Redis as the target caching backend

Verify implementation details against the actual repository before making assumptions.

Development Guidelines

- Inspect the existing architecture before modifying code.
- Follow established naming conventions and project structure.
- Prefer small, focused changes over broad refactoring.
- Avoid duplicating existing functionality.
- Do not change public API behavior unless required by the assignment.
- Do not introduce dependencies without a clear justification.
- Never commit credentials, API keys, or other secrets.
- Do not invent files, functions, or configuration options.

Testing

- Inspect and run existing tests before making changes.
- Add tests for every new feature and important edge case.
- Test Redis integration and cache invalidation.
- Test graceful behavior when Redis is unavailable.
- Run relevant tests after each implementation stage.
- Report failing tests honestly. Never claim that tests pass without running them.

Git Workflow

- Make small, logical commits throughout development.
- Keep unrelated changes out of commits.
- Never commit `.env` files, credentials, virtual environments, or temporary files.
- Do not rewrite Git history or force-push without explicit permission.

Token Efficiency

- Inspect only files relevant to the current task.
- Avoid rereading files unless necessary.
- Do not repeat previously established findings.
- Keep explanations and progress reports concise.
- Avoid unnecessary command execution.
- Ask before performing broad refactoring or expensive operations.

Documentation

- Document new configuration options and environment variables.
- Update relevant API documentation when endpoints change.
- Keep setup and testing instructions accurate.
- Explain non-obvious implementation decisions where useful.