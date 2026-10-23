# Portfolio

Static HTML/CSS/JS site. No build step.

## Structure
- `index.html` home: hero, work grid, about, contact
- `projects/project-template.html` copy this for each case study
- `css/tokens.css` colours, type, spacing, radii (edit here to restyle everything)
- `css/style.css` components and layout
- `assets/` images and `cv.pdf`

## Preview
`python3 -m http.server 8000` then open http://localhost:8000

## Publish
Push to GitHub and enable Pages, or connect the repo to Netlify or Cloudflare Pages. Every push to `main` deploys.

## Workflow with Claude Code
Work on a branch, review the diff, merge to `main` to publish.
