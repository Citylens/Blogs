# Citylens Articles Repository

This repository contains the articles and blog posts for the Citylens website. All content is written in Markdown format with YAML frontmatter for metadata.

## Branch Structure

- `main` - Production-ready content
- `develop` - Staging and testing
- Feature branches - Individual articles or content updates

## Contributing

1. Create a new feature branch from `develop`:
   ```bash
   git checkout develop
   git checkout -b feature/new-article-name
   ```

2. Add your article in the `content/articles` directory
3. Follow the naming convention: `YYYY-MM-DD-article-slug.md`
4. Submit a pull request to the `develop` branch
5. After review and testing, content will be merged to `main`

## Article Format

Each article should include the following frontmatter:

```yaml
---
title: "Article Title"
type: "article-type"  # case-study, news, research, or projects
description: "Brief description of the article"
date: YYYY-MM-DD
image: "URL to header image"
readTime: "X min read"
---
```

## Article Types

- `case-study`: Real-world implementations and results
- `news`: Current events and updates
- `research`: Academic and technical research papers
- `projects`: Ongoing or completed project showcases

## Development

To run the content locally:

```bash
npm install
npm run dev
```

## Deployment

- Content merged to `main` is automatically deployed to production
- Content merged to `develop` is deployed to staging for review

## License

All content is © Citylens. All rights reserved.
