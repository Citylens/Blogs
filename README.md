# Citylens Blog Articles

This repository contains the articles and blog posts for the Citylens website. All content is written in Markdown format with YAML frontmatter for metadata.

## Repository Structure

```
├── content/
│   └── articles/           # Blog posts and articles
├── .github/
│   └── workflows/          # GitHub Actions workflows
└── README.md              # This file
```

## Article Format

Each article should follow this format:

```markdown
---
title: "Your Article Title"
type: "article-type"  # case-study, news, research, or projects
description: "Brief description"
date: "YYYY-MM-DD"
image: "URL to header image"
readTime: "X min read"
---

Article content goes here...
```

## Article Types

- `case-study`: Real-world implementations and results
- `news`: Current events and updates
- `research`: Academic and technical research papers
- `projects`: Ongoing or completed project showcases

## Contributing

1. Create a new branch for your article:
   ```bash
   git checkout -b feature/new-article-name
   ```

2. Add your article in the `content/articles` directory following the naming convention:
   ```
   YYYY-MM-DD-article-slug.md
   ```

3. Submit a pull request to the `main` branch

## Development

To run the content locally:

```bash
npm install
npm run dev
```

## Deployment

The site is automatically deployed through GitHub Actions when changes are pushed to the main branch. The deployment process includes:

1. Building the site
2. Running tests
3. Deploying to production

## Environment Variables

Make sure to set up these environment variables in your deployment environment:

```
VITE_GITHUB_OWNER=Citylens
VITE_GITHUB_REPO=Blogs
VITE_GITHUB_TOKEN=your-github-token
```

## License

© 2024 Citylens. All rights reserved.
