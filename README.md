# gigue public docs

The public Gigue documentation site (Mintlify), served at the Gigue docs domain.

## Editing

- Pages are MDX under this repo; navigation is configured in `docs.json` (the only config — there is no `mint.json`).
- Reference docs are generated, not hand-written — do not add hand-written API reference here.
- Open a PR; **do not push to the default branch** (Mintlify redeploys the live public site on merge).

## Local preview

```bash
npx mint dev
```

## More

This repo is the `public` tier of the gigue docs program. See the program spec in
`internal-toolkit/docs/plan/2026-06-17-docs-program-design.md`.
