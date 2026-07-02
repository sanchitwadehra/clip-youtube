# Claude Code Context

## Instructions for Claude

- **Do NOT add co-author signatures to commits** (no `Co-Authored-By: Claude...` lines)
- Use Conventional Commits format for commit messages: `type(scope): description` (e.g. `feat(extension): ...`, `fix: ...`, `refactor: ...`, `docs: ...`, `chore: ...`)
- Use `uv` for Python package management, not pip
- Use `pnpm` for JavaScript/TypeScript package management, not npm/yarn
- **Keep files under 150 lines** - if a file exceeds this, split into separate modules
