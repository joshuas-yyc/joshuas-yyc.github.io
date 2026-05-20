---
title: Personal Site
type: experiment
purpose: Minimal static personal page — living signal hub
scope: index.html + style.css only, no build tools
termination_condition: Deployed to GitHub Pages or archived if not deployed within 90 days
---

## Deploy to GitHub Pages

1. Create a new repo on GitHub named `yourusername.github.io`
2. `git init && git add . && git commit -m "init"`
3. `git remote add origin https://github.com/yourusername/yourusername.github.io`
4. `git push -u origin main`

Site goes live at `https://yourusername.github.io` within minutes. No build step required.

## To update output cards

In `index.html`, replace each `output-card--empty` block:

```html
<article class="output-card" role="listitem">
  <span class="card-type">project</span>
  <a class="card-title" href="https://...">Title of work</a>
</article>
```
