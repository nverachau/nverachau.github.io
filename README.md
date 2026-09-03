# nverachau.com static site

This is a static replacement for the current Google Sites website.

## Local preview

Run:

```sh
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Updating

- Edit page copy directly in the `.html` files.
- Edit visual design in `styles.css`.
- Edit small interactions in `script.js`.
- Put the current CV at `assets/vera-chau-cv.pdf`.
- Put public paper PDFs in `assets/papers/`.
- Put research figures in `assets/figures/`.

Suggested asset names:

```text
assets/
  vera-chau-cv.pdf
  papers/
    technology-adoption-network-effects.pdf
    integrated-intermediation-fintech-market-power.pdf
  figures/
    technology-adoption-main.png
    intermediation-main.png
    aggregate-technological-change-main.png
```

## Hosting

This can be hosted on GitHub Pages, Netlify, Vercel, Cloudflare Pages, or any static hosting provider.

## GitHub

This folder can be pushed to a GitHub repository as-is. After creating an empty GitHub repo, add it as the remote:

```sh
git remote add origin git@github.com:YOUR-USERNAME/YOUR-REPO.git
git branch -M main
git push -u origin main
```
