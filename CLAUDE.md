# ebenowen.com

Personal portfolio site for Eben Owen (Technical Producer & Post-Production).

## How it works
- Plain static site: everything (HTML, CSS, JS) lives in `index.html`. No build step, no framework.
- Hosted on GitHub Pages from repo `ebenowenn/ebenowenn.github.io`, branch `main`, root folder.
- `CNAME` points the custom domain `ebenowen.com` at Pages — don't delete or rename it.
- Pushing to `main` publishes the site live (usually within 1–2 minutes).

## Page sections (ids in index.html)
`#hero`, `#about`, `#showreel`, `#skills`, `#experience`, `#work`, `#contact`

## Assets
- `photo.jpg`, `thumbnail.jpg`, `logo-*.png` — images used on the page
- `cv_eben_owen.pdf`, `Eben_Owen_AI_Agent_Portfolio.pdf` — linked downloads

## Workflow
1. Edit `index.html` (or add assets).
2. Preview locally with the `ebenowen-site` config in `.claude/launch.json` (http://localhost:4321) and check desktop + mobile widths.
3. Show the change, then commit and push to `main` only once Eben approves — pushing makes it live.
