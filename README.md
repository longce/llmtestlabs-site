# LLMTest Labs — official site

Single-page static site for [llmtestlabs.com](https://llmtestlabs.com). No build step: plain HTML + CSS, assets in `assets/`.

## Local preview

Open `index.html` in a browser, or:

```
python3 -m http.server 8000
```

## Deploy (GitHub Pages)

Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `(root)`.
`.nojekyll` is present so Jekyll does not touch the files.

To attach the custom domain later: add a `CNAME` file containing `llmtestlabs.com`,
then point the domain's DNS at GitHub Pages.
