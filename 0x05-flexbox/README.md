# 0x05 – Flexbox

> Build modern, flexible layouts with confidence.

## Why This Module Matters

Before Flexbox, creating even simple layouts (centering content, equal-height cards, navigation bars, sidebars) required fragile CSS hacks. Flexbox solved these problems cleanly and became the foundation of modern CSS layout.

Almost every real interface you will build uses Flexbox: navbars, card rows, form controls, media objects, footers, and component-level alignment. Mastering it here will make Grid, responsive design, and component work much easier.

This module focuses on deep understanding and practical patterns, not just memorizing properties.

## Learning Goals

By the end of this module, you should be able to:

- Create flex containers and control direction and wrapping
- Align and distribute items on the main and cross axes
- Control how individual items grow, shrink, and size themselves
- Build common real-world patterns (navbar, card rows, media objects, sidebars)
- Center content both horizontally and vertically with ease
- Debug flex layouts using browser DevTools
- Decide when Flexbox is the right tool

## Topics

### Flex Container
`display: flex` turns an element into a flex container. Its direct children become flex items.

### Direction & Wrapping
`flex-direction` and `flex-wrap` control the flow of items (row, column, wrapping).

### Alignment
`justify-content` (main axis) and `align-items` / `align-self` (cross axis) give precise control over positioning and distribution.

### Flex Item Properties
`flex-grow`, `flex-shrink`, `flex-basis`, and the `flex` shorthand control how items size themselves relative to one another.

### Common Patterns
Navigation bars, equal-height cards, media objects, centered content, and simple sidebars.

## What You'll Build

### Exercises

1. `0-flex_basics.html` + `0-flex_basics.css`
2. `1-alignment.html` + `1-alignment.css`
3. `2-flex_items.html` + `2-flex_items.css`
4. `3-navbar.html` + `3-navbar.css`
5. `4-cards_row.html` + `4-cards_row.css`
6. `5-media_object.html` + `5-media_object.css`

### Project

`mini-project-pricing_section.html` + `mini-project-pricing_section.css`

A complete pricing section with a header and card row built entirely with Flexbox.

## Expected Outcome

By the end of this module you should be able to:

- Build a navigation bar without struggle
- Create equal-height card layouts
- Center elements horizontally and vertically
- Control spacing and growth of flex items intentionally
- Read and debug flex layouts in DevTools
- Combine multiple flex techniques in one component

## Required Files

0x05-flexbox/  
├── README.md  
├── CHECKLIST.md  
├── 0-flex_basics.html  
├── 0-flex_basics.css  
├── 1-alignment.html  
├── 1-alignment.css  
├── 2-flex_items.html  
├── 2-flex_items.css  
├── 3-navbar.html  
├── 3-navbar.css  
├── 4-cards_row.html  
├── 4-cards_row.css  
├── 5-media_object.html  
├── 5-media_object.css  
├── mini-project-pricing_section.html  
└── mini-project-pricing_section.css


## Important Rules

- Follow the required filenames exactly
- Use external CSS files
- Use Flexbox as the primary layout method
- Do not use CSS Grid yet
- Prefer clean, readable class names
- Test thoroughly and use DevTools (Flexbox inspector is very - helpful)
- Do not copy another student’s solution
- Follow the requirements in CHECKLIST.md

## Resources

MDN – Flexbox
CSS-Tricks – A Complete Guide to Flexbox
MDN – align-items
MDN – justify-content
Flexbox Froggy (optional practice game)

## Before You Move On
You should be able to build a navbar, a row of cards, and a centered hero section without looking up the basic properties.
You should understand why an item grows or shrinks, not just which property to use.