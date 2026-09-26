# Wedding Reception Proposal — Abuja, April 2027

A single self-contained, mobile-first proposal page. All images and video are
embedded as base64 inside `index.html`, so there are no separate asset files
to manage — one file is the entire site.

## Deploy on Vercel (via GitHub)

1. Push this folder to a new GitHub repository, with `index.html` at the repo root.
2. Go to vercel.com → **Add New Project** → **Import Git Repository** → select the repo.
3. Framework preset: **Other** (static site, no build step).
4. Build command: leave blank. Output directory: leave as default.
5. Click **Deploy**.

Vercel will give you a live `.vercel.app` URL immediately. A custom domain can
be attached later under Project → Settings → Domains.

## Editing in Cursor

Open `index.html` directly — all styles and scripts are inline in the same
file (`<style>` in the `<head>`, `<script>` before `</body>`). Search for
section IDs (`#food`, `#decor`, `#media`, `#entertainment`, `#logistics`,
`#security`, `#fees`, `#budget`) to jump to a section quickly.

## Notes

- Photography section is currently using sample/reference images pending the
  final selection from the photographer.
- Pricing marked **TBD** in the Working Budget section is intentional —
  those line items are still being finalized with the client.
