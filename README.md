# basukinath.github.io

Personal portfolio — hand-built, single self-contained `index.html`, no template, no build step, no JavaScript framework (the mobile menu is a pure-CSS checkbox toggle).

## Files

- `index.html` — the whole site. Dark, terminal-inspired, one page.
- `resume.pdf` — downloadable résumé, linked from the nav and hero.

## Deploying (replacing the current site)

This repo currently runs the "Hyperspace" HTML5 UP template (`assets/`, `images/`, `generic.html`, `elements.html`, `LICENSE.txt`). To swap it for this redesign:

1. In the repo, delete: `assets/`, `images/`, `generic.html`, `elements.html`. (`LICENSE.txt` can stay or go — your call.)
2. Add `index.html` and `resume.pdf` from this folder, overwriting the existing `index.html`.
3. Commit and push to `main` (or whichever branch Pages is set to build from — check **Settings → Pages**).
4. GitHub Pages rebuilds automatically in a minute or two. Hard-refresh `https://basukinath.github.io/` to see it (browsers cache GitHub Pages aggressively — a normal refresh may still show the old template).

## Editing later

Everything — HTML, CSS, copy — lives in `index.html`. There's no build pipeline: edit the file, commit, push. Content sections are ordered: hero → about → skills → experience → impact → education/leadership/certifications → book → contact.
