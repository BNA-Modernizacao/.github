# BNA Modernização Guidelines

BNA Modernizacao & Capgemini

## Code Chnages:

All code changes should be done under a branch follow the rules underneath:

- No direct commits are allowed to `main` branch! (exc edge cases).
- All work done work must:
  - Be in a branch following the branching name convetion bellow.
  - All commits in this branch should follow the commit message convention bellow.
  - Have a Pull Request open to `main` that should be reviewed by someone else.
  - Can be merged to `main` only after review and approval.

## Intervention Type

- Bugfix: to fix non production bugs found
- Hotfix: to fix any production bugs found
- Documentation: for any documention update, fix intended
- Feature: to development of new features or characteristics 

## Commit Message Convention:

Pattern: `(intervention-type): commit message`
Examples:
  - `(feature): add swagger on endpoint ABC`
  - `(bugfix): remove service useless sanitization`

## Branching Name Convention

Rules:

1. Lowercase and Hyphen-Separated
2. Alphanumeric Characters: Use only alphanumeric characters (a-z, 0–9)
3. No Continuous Hyphen or Trailing Hyphens
5. Descriptive: Branch names should be descriptive and concise, ideally reflecting the work done on the branch. 

### Branch Prefixes

- Feature Branches: feature/ (e.g., `feature/audio-chat`). 
- Bugfix Branches: bugfix/ (e.g., `bugfix/wrong-score`). 
- Hotfix Branches: hotfix/ for critical production bug fixes (e.g., `hotfix/critical-payment-issue`). 
- Documentation Branches: docs/ for writing, updating, or fixing documentation (e.g., `docs/assets-optimization`)

#### If there's a task/issue ticket associated

Pattern: `interventiontype/ticketnumber-featurename` 

 *Ticket number can be the Issue number in Github Board*
 
Examples:
- `feature/23-add-swagger-to-abc`
- `bugfix/5-remove-method-abc`
