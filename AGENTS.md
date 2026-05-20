# AGENTS.md

This is a Quarto HTML book for active notes on auth, security, and identity provider strategy.

## Working Rules

- Keep content book-like, concise, and practical.
- Put chapter source under `contents/`, grouped by topic.
- Wire every new chapter in `_quarto.yml` before rendering.
- Prefer `.qmd` for prose-first chapters.
- Preserve useful supplied prose, but remove chat residue and assistant follow-up offers.
- Run `quarto render` before committing.
- Commit source files only; `_book/` and `.quarto/` are generated.
- Use Conventional Commits, for example `feat(book): add identity provider strategy chapter`.

## Current Structure

- `index.qmd` - preface
- `contents/` - future chapters

## Publishing

- Public site: https://auth-notes-lightbridge.netlify.app
- Netlify build config: `netlify.toml`
