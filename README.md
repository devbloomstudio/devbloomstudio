# Bloom Studios — website

Static website for Bloom Studios (Tirana). Plain HTML, no build step.

- `index.html`: Home
- `work.html`: Work (Brand Identity projects live inside this page)
- `social.html`, `content.html`: category pages
- `studio.html`, `career.html`, `privacy.html`, `terms.html`
- one `.html` page per client project
- `assets/`, `covers/`, `reel/`, `media/`: images, videos and fonts

## Publish with GitHub Pages

1. Create a new repository on GitHub (e.g. `bloom-studios-site`).
2. Upload the contents of this folder to the root of the repository.
   There are ~790 files, more than the 100-file limit of GitHub's web uploader,
   so use **GitHub Desktop** (or `git push`).
3. In the repository: **Settings → Pages → Build and deployment**,
   Source: *Deploy from a branch*, Branch: `main`, folder `/ (root)`, Save.
4. After a minute the site is live at `https://<username>.github.io/<repository>/`.

## Custom domain (bloomstudios.eu)

In **Settings → Pages → Custom domain**, enter the domain and follow GitHub's
DNS instructions (A records / CNAME at your domain registrar), then enable
*Enforce HTTPS*.
