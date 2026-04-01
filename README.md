# ebiya.sg Blog

A Jekyll blog for ornamental fish, aquaculture, and Singapore aquarium hobbyists.

**Live site:** https://viralberryai.github.io/jekyll-blog-auto

## Stack

- [Jekyll](https://jekyllrb.com/) 4.3
- Hosted on GitHub Pages via GitHub Actions

## Local Development

```bash
bundle install
bundle exec jekyll serve --future
```

Open http://localhost:4000

## Adding Posts

Create a file in `_posts/` with the naming format:

```
YYYY-MM-DD-your-post-title.md
```

With front matter:

```yaml
---
title: "Your Post Title"
date: YYYY-MM-DD
categories: [Category]
tags: [tag1, tag2]
excerpt: "A short description."
---
```

## Deploy

Push to `main` — GitHub Actions builds and deploys to GitHub Pages automatically.
