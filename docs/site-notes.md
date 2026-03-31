# jeremyknows.com Site Notes

This repo is the live website project for **jeremyknows.com**.

## What lives here
- `index.html` — the current one-page site
- `assets/` — local images used by the site
- `vercel.json` — deployment config
- `docs/` — lightweight notes on purpose, source-of-truth, and maintenance

## Site purpose
This site is intentionally a **one-page personal site**.
Its job is not to be a full portfolio or CMS.
Its job is to create enough clarity and confidence that the right person reaches out.

Core structure:
1. Above-the-fold identity and positioning
2. What Jeremy does
3. What Jeremy has built
4. Where to find/contact him

## Canonical source docs
The private preserved source now lives in:
- `~/projects/jeremyknows-studio/SOURCE-OF-TRUTH.md`

That file points to the current brand, site, README, and asset truth.

Current upstream references include:
- Brand strategy guide: `~/projects/jeremyknows-studio/docs/strategy/jeremyknows-brand-identity-2026-03-28.md`
- Visual identity guide: `~/projects/jeremyknows-studio/docs/visual/jeremyknows-visual-identity-2026-03-28.md`
- Final PDF brand guide: `~/projects/jeremyknows-studio/exports/jeremyknows-brand-guide-v2.pdf`
- Working HTML source used during build: `~/.openclaw/agents/main/workspace/docs/html/jeremyknows-site-v3.html`

## Relationship to other repos
- `~/projects/jeremyknows.com` = website
- `~/projects/jeremyknows` = GitHub profile repo

The voice, visual language, and flagship project framing should stay in sync across both.

## Deployment
Current deployment target: Vercel.
If the domain is pointed correctly, this repo should remain the production source for jeremyknows.com.

## Maintenance notes
- Prefer local asset paths over remote/CDN references.
- Keep the site static unless there is a strong reason to add complexity.
- If brand positioning changes, update the canonical docs first, then mirror the change here.

## Notes
This repo is the public website artifact, not the master archive of every draft and asset.
