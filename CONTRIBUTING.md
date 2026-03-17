# Contributing Guide

Thanks for contributing to dress-guide.

## Branching

Use branch names with `codex/` prefix, for example:
- `codex/feature-wardrobe-api`
- `codex/fix-weather-cache`

## Commit Message

Use clear, scoped commit messages:
- `feat: add wardrobe list endpoint`
- `fix: handle weather API timeout fallback`
- `docs: update architecture diagram`

## Pull Request Checklist

Before opening a PR, make sure:
- Changes are focused and minimal
- Docs are updated if behavior changes
- No secrets are committed
- New env vars are added to `.env.example`

## Coding Notes

- Keep APIs versioned under `/api/v1`
- Prefer backward-compatible schema changes
- Add logs around recommendation generation and job runs

## Security

- Never commit real keys or tokens
- Use placeholders in samples and docs
- Report security issues privately to repository maintainers
