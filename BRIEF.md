# Design Brief: IT Specialist Portfolio

## Project Overview

- **Project**: Personal portfolio website for IT specialist
- **User**: Oussama Khobzi
- **Purpose**: Showcase IT skills (networking, maintenance, sys admin) to secure employment/contracts
- **Target Users**: IT managers, CTOs, business owners seeking IT support

## Design Direction

### Style: Technical Brutalism

Industrial, utilitarian, technical drawing aesthetic. Exposed structure, raw materials, functional over decorative. Think technical documentation meets terminal interface, but elevated.

### Color Strategy: Full Palette

- **Background**: Raw concrete gray (#1a1a1a)
- **Foreground**: Off-white (#f5f5f0)
- **Accent**: Industrial amber (#d4a017) — used sparingly for emphasis
- **Borders**: Visible 2px borders in steel gray (#4a4a4a)
- **No gradients, no soft shadows**

### Typography

- **Primary**: JetBrains Mono (monospace, technical feel)
- **Scale**: Large display text for name, utilitarian body
- **Weight**: Bold headings (700), regular body (400)

### Layout

- Grid-based with visible structural borders
- Exposed grid lines (2px solid)
- Asymmetric sections to break monotony
- Variable spacing: tight (16px) to generous (64px)

### Components

1. **Hero**: Large name, title, minimal tagline
2. **Services Grid**: What I do, bordered cards
3. **Skills List**: Technical, enumerated
4. **Contact**: Direct, no-fluff CTA

### Anti-Goals

- No gradient text
- No glassmorphism
- No hero metrics
- No AI-slop design patterns
- No decorative elements that don't serve function
- No em dashes

### References

- Technical documentation layouts
- Terminal/CLI aesthetics
- Industrial design blueprints

### States

- Default: Raw, structural
- Hover: Inverted colors on interactive elements only
- Focus: Visible outline (2px amber)

### Responsive

- Desktop: Full grid layout
- Tablet: Simplified 2-col
- Mobile: Single column, stacked

## Acceptance Criteria

1. Page loads without layout shift
2. All text readable (WCAG AA)
3. Hover states on all interactive elements
4. Responsive at 320px, 768px, 1200px+
5. Passes AI slop test (looks hand-crafted, not generated)