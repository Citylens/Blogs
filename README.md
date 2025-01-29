# Citylens Articles Repository

This repository contains the articles and blog posts for the Citylens website. All content is written in Markdown format with YAML frontmatter for metadata.

## Directory Structure

```
content/
└── articles/
    ├── 2024-02-15-barcelona-smart-city.md
    ├── 2024-02-10-predictive-analytics-study.md
    ├── 2024-02-01-singapore-energy.md
    └── 2024-01-25-damascus-recoding.md
```

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

## Contributing

1. Create a new branch for your article
2. Add your article in the `content/articles` directory
3. Follow the naming convention: `YYYY-MM-DD-article-slug.md`
4. Submit a pull request for review

## Development

To run the content locally:

```bash
npm install
npm run dev
```

## License

All content is © Citylens. All rights reserved.
