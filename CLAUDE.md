# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Docusaurus 3.4.0 documentation site for "缠中说禅" (Chan Zhong Shuo Chan) blog content. The site contains 1135+ articles organized by category and timeline.

## Commands

```bash
# Install dependencies
npm install

# Start development server (localhost:3000)
npm start

# Build for production (requires 8GB memory)
npm run build

# Serve built site locally
npm run serve

# Clear Docusaurus cache
npm run clear
```

## Architecture

```
chzhshch-blog/
├── docs/              # All markdown content (1135+ articles)
├── sidebars/          # Individual sidebar configurations
├── src/
│   ├── components/    # React components
│   ├── css/          # Global styles (custom.css)
│   ├── pages/        # Custom pages
│   ├── plugins/      # Docusaurus plugins (remark-adsense.js)
│   └── theme/        # Theme overrides (_Navbar/Content/)
├── static/           # Static assets (images, favicon)
├── docusaurus.config.js  # Main site configuration
└── sidebars.js       # Aggregates all sidebar definitions
```

## Key Conventions

### Content Organization
- All docs in `docs/` directory as Markdown files
- Sidebars defined in `sidebars/` directory, aggregated in `sidebars.js`
- Categories: stocks, economics, essays, math, music, entertainment, confucius, zen, poems, fluid

### Tech Stack
- **Framework**: Docusaurus 3.4.0 with React 18
- **Language**: TypeScript/JavaScript (Node >=18.0)
- **Styling**: CSS Modules + Infima CSS framework
- **Math**: KaTeX via `remark-math` and `rehype-katex` (use `$$` for display math)
- **Search**: Local search via `@easyops-cn/docusaurus-search-local`

### Code Patterns
- Components: functional React components with TypeScript props
- CSS: Use CSS Modules (`styles.module.css`) for component-scoped styles
- Imports: ES6 imports, group React first, then external libs, then internal

### Configuration
- Default locale: `zh-Hans` (Simplified Chinese)
- Base URL: `/`, deployed to `https://chzhshch.blog`
- Build memory: 8GB (`--max-old-space-size=8192`)

## Deployment

GitHub Actions workflow (`.github/workflows/prod-release-gh.yml`) deploys to GitHub Pages on push to `main` branch.

## Related Documentation

See `AGENTS.md` for more detailed development guidelines.
