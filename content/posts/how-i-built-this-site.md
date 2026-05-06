---
title: "Why I Built This Portfolio With Hugo"
date: 2025-09-01
tags: ["meta", "hugo", "github-pages"]
description: "The tech stack behind this site and why I chose it."
---

## Why I needed a portfolio

As part of the Professional Networking module at Howest, we're asked to build an e-portfolio - a personal website that brings together event reflections, project write-ups, and other professional activities. Rather than just meeting the requirement, I wanted to build something that could serve me beyond school: a clean, professional site I'd be happy to link on a CV or LinkedIn profile.

## Choosing the tech stack

I considered a few options. WordPress and Wix are quick to set up, but they feel generic and don't reflect what I'm going for. Building everything from scratch in HTML/CSS/JS would give me full control, but seemed like overkill for what is essentially a blog with articles.

I landed on Hugo, a static site generator, paired with GitHub Pages for hosting. Here's why:

- **Developer-friendly** - I write posts in Markdown, which is fast and distraction-free.
- **Free** - GitHub Pages hosts the site at no cost, and the URL stays active after graduation.
- **Fast and secure** - no database, no server-side code, just static HTML files.
- **Professional-looking** - I'm using the PaperMod theme, which is minimal and clean without looking like a default template.

## The tech stack at a glance

| Component | Tool |
|---|---|
| Static site generator | Hugo |
| Theme | PaperMod |
| Hosting | GitHub Pages |
| Deployment | GitHub Actions (auto-deploys on push) |
| Version control | Git + GitHub |

## How I add a new post

Adding content is simple:

1. Create a new `.md` file in the `content/posts/` folder.
2. Write the reflection using Markdown.
3. Commit and push to GitHub.

GitHub Actions picks it up, builds the site, and deploys it automatically. The whole process takes less than a minute once the content is written. No FTP uploads, no dashboard logins - just Git.

## What I'd do differently

If I had more time, I'd probably explore customizing the theme further or even building my own. But for the purpose of this portfolio, Hugo + PaperMod strikes the right balance between effort and result.