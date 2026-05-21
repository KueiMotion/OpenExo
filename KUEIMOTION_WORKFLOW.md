# KueiMotion branch workflow

This repository is a KueiMotion fork of `naubiomech/OpenExo` and is used as a reference project.

## Branch rules

- Each contributor works on a branch named after their GitHub username.
- `dcyt888888-cell` works on the `dcyt888888-cell` branch.
- New collaborators should create and push only to their own username branch.
- Changes intended for `main` should go through a pull request.
- `main` is protected and updates are restricted to `dcyt888888-cell`.

## Starting a personal branch

```bash
git checkout main
git pull
git checkout -b <github-username>
git push -u origin <github-username>
```

Keep your personal branch current with `main` before opening a pull request.
