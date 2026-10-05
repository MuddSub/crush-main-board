# Contributing

## Branching Model (inspired by Analog Circuits Engineering Lab and GitHub Flow)

- `main`: all feature branches are manually squash-merged here by repository admins.
- Feature branches: short-lived, named `<task>` (e.g., `silkscreen_cleanup`).

## Workflow

1. Branch from `main` (temporarily, until this message is removed, branch from `PCB-Modifications-FA25`)
2. Open a PR into `main` (temporarily into `PCB-Modifications-FA25`) when ready for review
3. Admins will manually merge your changes

## Commit Messages

Follow the [Conventional Commits](https://www.conventionalcommits.org/) format:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

(e.g., `feat: added standardized zooming indicators`)

## Commit Naming

| Name     | Description                           |
|----------|---------------------------------------|
| feat     | a new feature                         |
| lib      | update to symbol or footprint library |
| fix      | a patch for a bug                     |
| docs     | update to documentation               |
| refactor | no external behavior changed          |
| test     | updates to test points                |
| chore    | maintenance and build tasks           |

If your commit doesn't fit smoothly into any of these categories, let us know, and we might add a new category!