# Project Name

## Overview
This project is structured to follow a Git workflow that includes branching for feature development, releases, and hotfixes.

## Branching Strategy
- **master**: The main branch, representing the stable production-ready code.
- **develop**: The development branch where features are integrated before release.
- **feature branches**: Used for developing individual features (e.g., `feature1`, `feature2`).
- **release branches**: Created to prepare a new production release (e.g., `release1`).
- **hotfix branches**: Used for urgent fixes directly on the master branch (e.g., `hotfix1`).

## Commits and Workflow up to First Release
1. **Commit A**: Initial commit on `master` branch with basic project setup.
2. **Commit B**: Created the `develop` branch from `master`.
3. **Commits C and D**: Developed `feature1` on a separate branch, then merged into `develop`.
4. **Commit E**: Merged `feature1` into `develop`.
5. **Commit F1**: Started `feature2` development.
6. **Commit G**: Bug fixes in `release1` branch.
7. **Commit H**: Merged `release1` into `master` for the first release, tagged as `v1.00`.
8. **Commit I**: Merged 'release1' back into 'develop' to keep branches in sync with production
