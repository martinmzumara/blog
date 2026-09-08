# Martin Mzumara — Blog

Static blog built with [Astro](https://astro.build), linked from the [portfolio](https://martinmzumara.github.io/).

## Writing a post

Add a Markdown file to `src/content/posts/`:

```md
---
title: 'Post Title'
description: 'One-line summary shown on cards and in search results.'
date: 2026-09-08
tag: 'Category'
device: 'laptop'   # optional: 'laptop' or 'phone'
---

Your content in Markdown.
```

The post list and article pages generate automatically, newest first.

## Development

```sh
npm install
npm run dev      # http://localhost:4321/blog/
npm run build    # outputs to dist/
```

## Deployment

Push to `main` — GitHub Actions builds and deploys to
https://martinmzumara.github.io/blog/ (enable GitHub Pages from Actions in repo settings).
