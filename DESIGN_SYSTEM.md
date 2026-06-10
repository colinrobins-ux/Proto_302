# NYT Bestseller × Ivy League Design System

This design system is based on the visual language in `nyt_ivy_league.html`. It captures the core UI patterns, color palette, typography, spacing, and component styles used in the page.

## Core tokens

- Colors:
  - `--ds-bg`: #0d0d0d
  - `--ds-surface`: #1a1a1a
  - `--ds-border`: #2a2a2a
  - `--ds-text`: #e8e4dc
  - `--ds-muted`: #888
  - `--ds-muted-strong`: #666
  - `--ds-heading`: #ffffff
  - `--ds-accent`: #c8a84b
  - `--ds-accent-soft`: #c8a84b22
  - `--ds-muted-alt`: #bbb
  - `--ds-placeholder`: #555
  - `--ds-row-hover`: #1a1a1a

- Typography:
  - Heading / body serif: `Georgia, serif`
  - UI and utility sans-serif: `Arial, sans-serif`

- Layout:
  - Page max width: 1100px
  - Base gap: 16px
  - Card radius: 8px
  - Filter pill radius: 20px
  - Table padding: 12px 14px

## Components

### Page shell
- `.ds-page`
- `.ds-header`
- `.ds-header-title`
- `.ds-header-copy`

### Stats cards
- `.ds-stats-row`
- `.ds-stat-card`
- `.ds-stat-number`
- `.ds-stat-label`

### Filters
- `.ds-filters`
- `.ds-filter-label`
- `.ds-filter-btn`
- `.ds-search`

### Table
- `.ds-table-wrap`
- `.ds-table`
- `.ds-table th`
- `.ds-table td`
- `.ds-sort-icon`
- `.ds-hidden`

### Badges and chips
- `.ds-badge`
- `.ds-genre-badge`
- `.ds-ivy-chip`
- `.ds-degree-type`
- `.ds-no-ivy`
- `.ds-note`
- `.ds-peak-years`

### Supporting patterns
- `.ds-legend`
- `.ds-legend-item`
- `.ds-legend-dot`
- `.ds-section-divider`
- `.ds-footnote`
- `.ds-count-badge`

## Ivy school palette

- `.ivy-harvard`: #e87a7a on #7b000022
- `.ivy-yale`: #6aaee8 on #00356b22
- `.ivy-princeton`: #e8b96a on #e77500221
- `.ivy-columbia`: #6a8ae8 on #0033a022
- `.ivy-penn`: #8ab0e8 on #01153622
- `.ivy-cornell`: #e87a7a on #b3182522
- `.ivy-dartmouth`: #6ae89a on #00703c22
- `.ivy-brown`: #c8a87a on #4e392722

## Usage guidance

Use this system for new pages that rely on the same data dashboard styling:
- dark mode dashboard background
- strong serif heading and author text
- compact data cards with gold accent
- soft pill badges for genres and school labels
- responsive table layout with sortable headings

## Next steps

1. Convert the existing `nyt_ivy_league.html` layout to use `.ds-*` class names.
2. Add JavaScript behavior for filtering and search when needed.
3. Expand the design system to include chart styles and article story components from the brief.
