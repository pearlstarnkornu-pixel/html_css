# 0x08 – Components & Patterns

> Build once. Reuse everywhere.

## Why This Module Matters

Real websites are not made of one-off pages. They are built from reusable components: buttons, cards, navigation bars, form controls, alerts, and more.

This module trains you to think in components. You will design small, polished UI pieces with clear structure and consistent naming, then combine them. This is the foundation of maintainable frontend work and prepares you for design systems and modern frameworks later.

## Learning Goals

By the end of this module, you should be able to:

- Build reusable button styles (primary, secondary, outline)
- Create flexible card components
- Style navigation patterns consistently
- Apply a simple naming convention (BEM-inspired)
- Combine components into a coherent UI section
- Keep CSS organized and reusable
- Document components in a simple showcase page

## Topics

### Component Thinking
A component is a reusable piece of UI with a clear purpose, consistent structure, and predictable styles.

### Buttons
Buttons communicate actions. Variants (primary, secondary, outline) help express hierarchy.

### Cards
Cards group related content. They should be flexible enough for different use cases.

### Navigation Patterns
Consistent nav styling improves usability and brand cohesion.

### Naming (BEM-inspired)
Use clear block/element/modifier style names  
(example: `card`, `card__title`, `card--featured`).

### Composition
Components become powerful when combined into sections and pages.

## What You'll Build

### Exercises

1. `0-buttons.html` + `0-buttons.css`
2. `1-cards.html` + `1-cards.css`
3. `2-navigation.html` + `2-navigation.css`
4. `3-form_controls.html` + `3-form_controls.css`
5. `4-alerts_badges.html` + `4-alerts_badges.css`

### Project

`mini-project-component_showcase.html` + `mini-project-component_showcase.css`

A living component showcase page — the start of your personal UI toolkit.

## Expected Outcome

By the end of this module you should be able to:

- Create reusable components instead of one-off styles
- Name classes clearly and consistently
- Build a small library of UI pieces you can reuse later
- Compose components into polished sections

## Required Files

0x08-components_and_patterns/
├── README.md
├── CHECKLIST.md
├── 0-buttons.html
├── 0-buttons.css
├── 1-cards.html
├── 1-cards.css
├── 2-navigation.html
├── 2-navigation.css
├── 3-form_controls.html
├── 3-form_controls.css
├── 4-alerts_badges.html
├── 4-alerts_badges.css
├── mini-project-component_showcase.html
└── mini-project-component_showcase.css

## Important Rules

- Follow the required filenames exactly
- Use external CSS files
- Prefer reusable class-based components
- Use clear naming (BEM-inspired recommended)
- Keep components independent and composable
- Do not copy another student’s solution
- Follow the requirements in CHECKLIST.md

## Resources

BEM Methodology - https://en.bem.info/methodology/
MDN – [CSS Organization](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Organizing)

## Before You Move On

You should be able to build a button set, a card, and a simple nav that you could drop into another project with minimal changes.