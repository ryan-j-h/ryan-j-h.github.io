# ryan-j-h.github.io

Personal website, served by GitHub Pages as plain static files (no build step; `.nojekyll` disables Jekyll).

## Structure

- `index.html` — all page content (bio, papers, abstracts)
- `style.css` — all styling
- `files/cv.pdf` — CV (replace the file to update; the link stays the same)
- `images/profile.jpg` — headshot
- `404.html` — not-found page

## Editing

Edit `index.html` directly. To add a paper, copy an existing `<article class="paper">` block and change the title, coauthors, and abstract. Abstracts fold in/out via the native `<details>` element — no JavaScript involved.

## Previewing

Open `index.html` in a browser. What you see is exactly what GitHub Pages serves.

## Deploying and reverting

Pages deploys from `master`. To publish changes from a branch, merge it into `master` and push. To undo a published change, `git revert` the merge commit (or reset `master` to the prior commit) and push.
