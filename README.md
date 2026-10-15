# Daniel Li · Portfolio

A lightweight engineering portfolio based on the existing `daniel-portfolio-v1` direction. Static HTML and CSS; no JavaScript, package installation, backend, database or build step.

## Preview and edit

```sh
python3 -m http.server 8091 --directory public
```

Open http://localhost:8091. Edit `public/index.html` for project/contact content, `public/styles.css` for presentation, and `public/resume.html` for the printable web résumé. Project images are local JPEGs in `public/assets/`. Keep alt text and links current when replacing a capture.

Vercel serves only `public/` via `vercel.json` (framework: Other, no build command). GitHub `main` is the production branch; pull requests receive Vercel previews once the Git integration is connected. Use the existing Hobby account; no paid infrastructure is needed.

[Content provenance and later README recommendations](docs/CONTENT.md). Project repositories and `daniel-li2021.github.io` are outside this repository's scope.
