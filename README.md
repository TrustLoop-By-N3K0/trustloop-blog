# trustloop-blog

Content marketing blog for TrustLoop.

## What this is

A standalone blog for case studies, founder updates, product tips, and SEO content. Keeping it separate from the app keeps the main TrustLoop repo focused on product code.

## Features

- Markdown/MDX posts
- Author pages
- Tags and categories
- RSS feed
- SEO metadata

## Tech stack

- Next.js App Router
- Tailwind CSS
- Contentlayer or CMS of your choice

## Getting started

```bash
cp env.example .env.local
npm install
npm run dev
```

## Adding a post

Add an `.mdx` file to `posts/` with frontmatter:

```yaml
---
title: "Why testimonials matter"
date: "2026-09-09"
author: "Your Name"
tags: ["testimonials", "marketing"]
---
```

## Deployment

Build command: `npm run build`  
Publish directory: `.next`

## License

MIT
