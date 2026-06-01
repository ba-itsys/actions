# Shared GitHub Actions

This repository contains shared GitHub Actions workflows and CI/CD patterns used across the **ba-itsys** organization.

## Purpose

By centralizing our workflows here, we ensure:
- **Consistency:** All repositories follow the same CI/CD standards.
- **Maintainability:** Updates to shared workflows are applied globally from a single location.
- **Efficiency:** Reduces duplication of workflow logic across multiple repositories.

## Usage

Repositories can reference these workflows using the following syntax:

```yaml
jobs:
  call-workflow:
    uses: ba-itsys/actions/.github/workflows/workflow-name.yml@main
```
