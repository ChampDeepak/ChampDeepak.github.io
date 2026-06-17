# Deepak's website

A minimalist personal site (blog · book summaries · portfolio · about) built with
[Jekyll](https://jekyllrb.com/) and hosted free on **GitHub Pages**. Black & white
theme with a light/dark toggle.

---

## 1. One-time setup (publish it live)

1. Create a **public** repo on GitHub.
   - For a URL like `https://USERNAME.github.io` → name the repo exactly `USERNAME.github.io`.
   - For a URL like `https://USERNAME.github.io/my-website` → name it `my-website`
     and set `baseurl: "/my-website"` in `_config.yml`.
2. Push this folder to that repo:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/USERNAME/REPO.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**,
   pick branch `main` and folder `/ (root)`. Save.
4. Wait ~1 minute. Your site is live. GitHub rebuilds it automatically on every push.

Then open `_config.yml` and set your real `email`, `title`, etc.

---

## 2. How to add content (the easy part)

You only ever add a markdown file and `git push`. No build step needed.

### Write a blog post
Create a file in `_posts/` named `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "My post title"
date: 2026-06-20
reading_time: "5 min read"
---

Your post body in **markdown**.
```

### Add a book summary
Create a file in `_books/` (any name, e.g. `sapiens.md`):

```markdown
---
title: "Sapiens"
author: "Yuval Noah Harari"
rating: 5
---

Your summary in markdown.
```

### Edit pages
- About → `about.md`
- Portfolio → `portfolio.md`
- Home intro → `index.html`

Then:
```bash
git add .
git commit -m "New post"
git push
```
The live site updates in about a minute.

> Tip: you can also create/edit files straight from the GitHub website
> (click **Add file → Create new file**) — no terminal needed.

---

## 3. Preview locally (optional)

Requires Ruby. Not needed to publish.

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```
