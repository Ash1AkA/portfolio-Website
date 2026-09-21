# Portfolio Website

Personal portfolio site for **Geesara Akash** — built with plain HTML, CSS, and JavaScript (no build step, no dependencies).

## Sections

- **Home** — welcome/hero with photo, name, and intro
- **About** — background and quick facts
- **Skills** — languages, frameworks, tools
- **Education** — timeline of education/experience
- **Projects** — showcase grid (placeholders — replace with your own)
- **Contact** — email/socials + a contact form (opens a pre-filled email, since this is a static site)

## Structure

```
index.html
css/style.css
js/script.js
.github/workflows/deploy.yml   # auto-deploys to GitHub Pages on push to main
```

## Local development

No build tools needed — just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Customizing

- Edit the placeholder project cards in the `#projects` section of `index.html` with your real repos.
- Update the `#skills` tags to match your actual stack.
- Replace the timeline items in `#education` with your real milestones.
- Swap the avatar image (currently your GitHub avatar) for a custom photo by replacing the `src` on the `.avatar` `<img>` in `index.html`.

## Deployment

This repo is set up to auto-deploy to **GitHub Pages** via GitHub Actions on every push to `main`. To finish enabling it:

1. Go to the repo **Settings → Pages**.
2. Under "Build and deployment", set **Source** to **GitHub Actions**.

The site will then be live at `https://ash1aka.github.io/portfolio-website/`.
