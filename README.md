# Dialer Cockpit (published mirror)

This repo exists only to serve `index.html` via GitHub Pages at a public
HTTPS URL. **Do not edit anything here directly** — it will be overwritten
by the next sync.

The real source is `cockpit/index.html` in the private
[`website-leads`](https://github.com/PDFAutomaton/website-leads) repo. A
GitHub Actions workflow there pushes the file here automatically on every
commit to `main` that touches it.

Nothing else from `website-leads` is ever copied here — this file is fully
self-contained, purely client-side (no backend, no API calls), and
contains no lead data, credentials, or business state. See that repo's
`STATE.md` for details.
