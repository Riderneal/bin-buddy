# Contributing

This repository belongs to **Team Dreamers**. Here's how we work on it.

## Branching

| Branch | Purpose |
|---|---|
| `main` | Always presentable. This is what judges see. |
| `feat/<name>` | New work — e.g. `feat/report-upload` |
| `fix/<name>` | Bug fixes |
| `docs/<name>` | Documentation only |

Never commit directly to `main` once the team is working in parallel — open a pull request.

## Commit messages

Use [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: add photo upload with geotag capture
fix: correct reward calculation on cancelled pickup
docs: expand feasibility section with revenue model
chore: update dependencies
```

## Pull requests

1. Branch off `main`.
2. Keep the PR focused on one thing.
3. Describe **what** changed and **why** in the description.
4. Get one teammate to review before merging.

## Repository conventions

- Documentation lives in `docs/`, one topic per file.
- The presentation lives in `presentation/` — update both the `.pptx` and the exported `.pdf` together.
- Slide images in `docs/slides/` are regenerated whenever the deck changes, so the README stays accurate.
- Never commit API keys, service-account JSON, or `.env` files. `.gitignore` covers the common cases, but check before you push.
