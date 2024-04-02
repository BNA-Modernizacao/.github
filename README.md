# BNA Modernização Guidelines

If you are changing code on repositories you are advised to follow the following rules bellow for better organization and work of every contributor:

## Code Changes:

All code changes should be done under the following rules underneath:

- No direct commits are allowed to `main` branch! (exc edge cases).
- All work done work must:
  - Be in a branch following the branching name convetion bellow.
  - All commits in this branch should follow the commit message convention bellow.
  - Have a Pull Request open to `main` that should be reviewed by someone else.
  - Can be merged to `main` only after review and approval.

## Intervention Type

- Bugfix: to fix non production bugs found.
- Hotfix: to fix any production bugs found.
- Documentation: for any documention update, fix or change intended.
- Feature: to development of new features or characteristics.

## Commit Message Convention:

Be Descriptive: commit messages should be descriptive and concise, ideally reflecting the change done on the commit. 

Pattern: `(intervention-type): commit message`
Examples:
  - `(feature): add swagger on endpoint ABC`
  - `(bugfix): remove service useless sanitization`

## Branching Name Convention

Rules:

1. Lowercase and Hyphen-Separated
2. Alphanumeric Characters: Use only alphanumeric characters (a-z, 0–9)
3. No Continuous Hyphen or Trailing Hyphens
5. Be Descriptive: Branch names should be descriptive and concise, ideally reflecting the result you want to achieve with the code changes on the branch. 

### Branch Prefixes

- Feature Branches: feature/ (e.g., `feature/audio-chat`). 
- Bugfix Branches: bugfix/ (e.g., `bugfix/wrong-score`). 
- Hotfix Branches: hotfix/ for critical production bug fixes (e.g., `hotfix/critical-payment-issue`). 
- Documentation Branches: docs/ for writing, updating, or fixing documentation (e.g., `docs/assets-optimization`)

#### If there's a task/issue ticket associated

Pattern: `interventiontype/ticketnumber-featurename` 

 *Ticket number can be the Issue number in Github Board*
 
Examples:
- `feature/23-introducing-swagger-abc`
- `bugfix/5-cleanup-services-abc`
