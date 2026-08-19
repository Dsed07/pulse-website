# pulselist.io

The public site for **PulseList** — a landing page, the privacy policy and the terms of
service.

## This directory is generated

Nothing here is edited by hand. It is built from `PRIVACY_POLICY.md` and
`TERMS_OF_SERVICE.md` in the private `pulse` repo by `scripts/build-site.py`, which is
where any change to the wording belongs. A hand-edit here is a second version of a legal
document, and the copy nobody maintains is the one the public reads.

The build strips two kinds of internal text that live in those source files — the
`Notes for review — not for publication` section, and inline `Reviewer` / `Draft for
legal review` blockquotes — and then *asserts* that none of it survived. If any does,
the build fails rather than publishing.

## Hosting

GitHub Pages, from `main`, custom domain `pulselist.io` (see `CNAME`).
