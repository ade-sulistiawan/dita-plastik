# AGENTS.md — Dita Plastik

## Commit & push policy (mandatory)

After completing any task that modifies files in this repository:

1. Run `git status` and `git diff` to inspect the changes.
2. Stage only the intended files (`git add <files>`).
3. Commit with a concise message describing the change (see commit style below).
4. Push to `origin` immediately: `git push origin main`.
5. Confirm the push succeeded before finishing the task.

Never leave committed-but-unpushed work behind, and never push secrets or files
that are not part of the change.

## Commit message style

Follow the existing repo style — a short imperative or descriptive one-liner,
optionally prefixed with a conventional type (`feat:`, `fix:`, etc.):
- `feat: add landing page hero`
- `Redesign as editorial-industrial theme`

## Project notes

- Vanilla HTML/CSS one-pager (`index.html`, `tokens.css`, `styles.css`).
- All colours and fonts must reference named tokens in `tokens.css`.
- Placeholder contact data (WhatsApp `6281234567890`, address, hours) lives in
  `index.html` — do not invent real numbers.