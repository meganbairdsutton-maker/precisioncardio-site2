# PrecisionCardio website

Static site. `index.html` is the homepage; everything (CSS, JS) is inside it. No build step.

## Deploy (Vercel)

1. Push this folder to a GitHub repository.
2. In Vercel, Add New Project, import the repository, leave every setting at its default (Framework: Other, no build command, output directory: root), Deploy.
3. Every push to `main` redeploys automatically.

Search engines are told not to index the site (`robots.txt` and a `noindex` meta tag) while it is a prototype. Remove both when the site launches.

## Update

Replace `index.html` with the newest export from the Claude session and push. Do not hand-edit the file; the source of record is the assembled flow.
