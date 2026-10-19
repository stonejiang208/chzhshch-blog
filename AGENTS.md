# AGENTS.md - chzhshch-blog Development Guide

This document provides guidelines for AI agents working on the chzhshch-blog repository, a Docusaurus-based documentation site for "缠中说禅" (Chan Zhong Shuo Chan) content.

## Project Overview

- **Type**: Docusaurus 3.4.0 documentation site
- **Language**: TypeScript/JavaScript with React
- **Primary Content**: Chinese documentation with mathematical notation support
- **Build System**: Node.js (>=18.0), npm/yarn

## Build & Development Commands

### Essential Commands

```bash
# Start development server
npm start
# or
yarn start

# Build for production (requires 8GB memory)
npm run build
# or  
yarn build

# Serve built site locally
npm run serve
# or
yarn serve

# Clear Docusaurus cache
npm run clear
# or
yarn clear
```

### Development Workflow

1. **Start development**: `npm start` - Runs on `http://localhost:3000` with hot reload
2. **Build for production**: `npm run build` - Outputs to `build/` directory
3. **Deploy**: `npm run deploy` - Deploys to GitHub Pages (configured in docusaurus.config.js)

### Memory Requirements
The build process requires significant memory. The `build` script includes `NODE_OPTIONS="--max-old-space-size=8192"` to allocate 8GB.

## Code Style & Conventions

### TypeScript/JavaScript

**Imports**:
- Use ES6 imports: `import React from 'react';`
- Group imports: React first, then external libraries, then internal modules
- Use named imports for Docusaurus components: `import {useThemeConfig} from '@docusaurus/theme-common';`

**TypeScript**:
- Use TypeScript for new components (`.tsx` extension)
- Define explicit types for props and state
- Example type definition pattern:
  ```typescript
  type FeatureItem = {
    title: string;
    Svg: React.ComponentType<React.ComponentProps<'svg'>>;
    description: JSX.Element;
  };
  ```

**Function Components**:
- Use functional components with React Hooks
- Export as default: `export default function ComponentName(): JSX.Element`
- Use destructuring for props: `function Feature({title, Svg, description}: FeatureItem)`

**Naming Conventions**:
- Components: PascalCase (`HomepageFeatures`, `NavbarContent`)
- Functions: camelCase (`useNavbarItems`, `splitNavbarItems`)
- Variables: camelCase (`featureList`, `mobileSidebar`)
- Constants: UPPER_SNAKE_CASE for true constants, otherwise camelCase

### CSS/Styling

**File Organization**:
- Global styles: `src/css/custom.css`
- Component-specific styles: `styles.module.css` alongside component
- Use CSS Modules for component-scoped styles

**CSS Conventions**:
- Use CSS custom properties (variables) defined in `:root`
- Follow Infima CSS framework conventions (Docusaurus default)
- Use responsive design principles
- Chinese font: 'Noto Sans SC' with weights 100-900

**Example CSS Module Import**:
```typescript
import styles from './styles.module.css';
// Usage: <div className={styles.featureSvg} />
```

### File Structure

```
src/
├── components/     # React components
├── css/           # Global styles
├── pages/         # Custom pages
├── plugins/       # Docusaurus plugins
└── theme/         # Theme overrides
```

## Configuration Files

### TypeScript Configuration
- `tsconfig.json`: Extends `@tsconfig/docusaurus/tsconfig.json`
- Base URL: `.` (project root)

### Docusaurus Configuration
- `docusaurus.config.js`: Main site configuration
- `sidebars.js`: Documentation sidebar definitions
- `babel.config.js`: Babel configuration for Docusaurus

### Key Docusaurus Configurations
- **Default locale**: `zh-Hans` (Simplified Chinese)
- **Search**: Local search with `@easyops-cn/docusaurus-search-local`
- **Math support**: KaTeX via `remark-math` and `rehype-katex`
- **Base URL**: `/` (root)
- **URL**: `https://chzhshch.blog`

## Content Management

### Documentation Structure
- All content in `docs/` directory
- Organized by category with sidebars
- Markdown files with YAML frontmatter
- Supports mathematical notation with `$$` LaTeX syntax

### Sidebar Organization
Multiple sidebars for different content categories:
- `timelineSidebar`: Chronological blog posts
- `stocksExtendedSidebar`: Stock trading tutorials
- `economicsSidebar`: Economic articles
- Various category-specific sidebars

### Markdown Features
- Math equations with KaTeX
- Code blocks with syntax highlighting
- Custom CSS classes for special content types
- AdSense integration via custom remark plugin

## Development Guidelines

### Adding New Components
1. Create component in `src/components/` with `.tsx` extension
2. Use TypeScript with explicit prop types
3. Include corresponding CSS module if needed
4. Export as default function component

### Theme Customization
- Override Docusaurus components via `src/theme/`
- Use `yarn swizzle` to eject theme components
- Example: `src/theme/_Navbar/Content/index.js` customizes navbar

### Plugin Development
- Custom plugins in `src/plugins/`
- Example: `remark-adsense.js` for AdSense integration
- Follow Docusaurus plugin API

### Error Handling
- Use try-catch for async operations
- Provide fallback UI for loading states
- Validate props with TypeScript
- Use React Error Boundaries for component errors

## Testing & Quality

### Code Quality
- No ESLint/Prettier configuration found - follow existing patterns
- Use TypeScript strict mode (inherited from Docusaurus config)
- Maintain consistent formatting with existing code

### Browser Support
- Production: `>0.5%`, not dead, not op_mini all
- Development: last versions of Chrome, Firefox, Safari

## Deployment

### Build Process
1. Run `npm run build` (requires 8GB memory)
2. Verify build output in `build/` directory
3. Test locally with `npm run serve`
4. Deploy with `npm run deploy` or manual deployment

### Environment Requirements
- Node.js >= 18.0
- 8GB+ RAM for building
- Git for deployment

## Special Considerations

### Chinese Language Support
- Font: 'Noto Sans SC' with comprehensive weight range
- Line height: 200% for readability
- Font size: 18px base
- Text justification for certain content types

### Mathematical Content
- KaTeX for mathematical notation
- Import KaTeX CSS via CDN
- Use `$$` for display math and `$` for inline math

### AdSense Integration
- Custom remark plugin for ad injection
- Ads placed after first heading in content
- Multiple ad slots configured

### Performance
- Large documentation site (1135+ articles)
- Memory-intensive build process
- Local search index for performance

## Troubleshooting

### Common Issues
1. **Build memory errors**: Ensure 8GB+ available, use `--max-old-space-size=8192`
2. **TypeScript errors**: Check Docusaurus type definitions
3. **Hot reload not working**: Run `npm run clear` and restart
4. **Missing dependencies**: Run `npm install` or `yarn install`

### Debugging
- Check browser console for React errors
- Verify TypeScript compilation
- Test individual components in isolation
- Use React Developer Tools

---

## 角色矩阵

| 角色 | 输入 | 输出 | 负责模块 |
|------|------|------|----------|
| **缠论专家** | 需求规格说明书 | 算法规格说明书、识别规则 | Chan_Theory/ |

### 缠论专家职责

**核心职责：**
1. **算法规格** — 将缠论理论（笔、线段、中枢、背驰等）转化为可实现的算法规范
2. **识别规则** — 定义各层级走势类型的判定逻辑与边界条件
3. **模块开发** — 负责 `Chan_Theory/` 模块的代码实现
4. **知识萃取** — 从博客内容中整理规则到 `docs/stone/` 目录

**知识来源与输出：**
- **输入源**: 
  - `/root/workspace/chzhshch-blog/*` (博客内容)
  - `/root/workspace/projects/C2-chanlun-v2/backend/3rd/chan.py` (开源算法实现)
- **输出目录**: `/root/workspace/chzhshch-blog/docs/stone/`
- **目的**: 快速检索缠论规则、算法边界条件、走势类型判定逻辑

**算法参考重点：**
- 特征序列法处理段 (Bi, Segment, Zone 识别)
- 笔、线段、中枢的自动化判定逻辑
- 背驰、买卖点的算法实现

**适用场景：**
- 股票买卖点分析
- 大盘趋势研判
- 交易策略制定
- 缠论算法实现

---

*This guide is based on analysis of the existing codebase. Follow existing patterns and conventions when making changes.*