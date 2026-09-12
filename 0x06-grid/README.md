# 0x06 – CSS Grid

> Create powerful two-dimensional layouts with precision.

## Why This Module Matters

Flexbox is excellent for one-dimensional layouts (rows *or* columns). CSS Grid is designed for two-dimensional layouts (rows *and* columns at the same time). Together they form the modern layout system of the web.

Grid shines for page structure, galleries, dashboards, magazine-style layouts, and any interface where you need precise control over both axes. Learning it well dramatically reduces the need for complicated nested structures and fragile positioning.

This module focuses on practical understanding and real patterns you will reuse constantly.

## Learning Goals

By the end of this module, you should be able to:

- Create grid containers and define rows and columns
- Control spacing with `gap`
- Place items using line-based placement (`grid-column`, `grid-row`)
- Use named grid areas for clear, maintainable layouts
- Align content inside the grid
- Build common patterns (galleries, dashboards, magazine layouts)
- Decide when to use Grid vs Flexbox
- Debug grid layouts with browser DevTools

## Topics

### Grid Container
`display: grid` turns an element into a grid container. You define tracks with `grid-template-columns` and `grid-template-rows`.

### Tracks & Gaps
Columns and rows form the structure. `gap` (and `row-gap` / `column-gap`) controls spacing between tracks.

### Item Placement
Items can be placed on specific grid lines or span multiple tracks using `grid-column` and `grid-row`.

### Named Grid Areas
`grid-template-areas` lets you design layouts visually with named regions — one of the most powerful and readable features of Grid.

### Alignment
`justify-items`, `align-items`, `justify-content`, and `align-content` control alignment of items and the grid itself.

### Grid vs Flexbox
Use Flexbox for component-level one-dimensional layout. Use Grid for two-dimensional page or section structure. They work great together.

## What You'll Build

### Exercises

1. `0-grid_basics.html` + `0-grid_basics.css`
2. `1-placement.html` + `1-placement.css`
3. `2-grid_areas.html` + `2-grid_areas.css`
4. `3-photo_gallery.html` + `3-photo_gallery.css`
5. `4-dashboard_layout.html` + `4-dashboard_layout.css`

### Project

`mini-project-magazine_layout.html` + `mini-project-magazine_layout.css`

A magazine-style page section that uses Grid for overall structure and named areas.

## Expected Outcome

By the end of this module you should be able to:

- Define a grid and place items intentionally
- Build a photo gallery and a simple dashboard layout
- Use named areas for clear page structure
- Combine Grid with Flexbox when appropriate
- Read and debug grid layouts in DevTools

## Required Files

0x06-grid/  
├── README.md  
├── CHECKLIST.md  
├── 0-grid_basics.html  
├── 0-grid_basics.css  
├── 1-placement.html  
├── 1-placement.css  
├── 2-grid_areas.html  
├── 2-grid_areas.css  
├── 3-photo_gallery.html  
├── 3-photo_gallery.css  
├── 4-dashboard_layout.html  
├── 4-dashboard_layout.css  
├── mini-project-magazine_layout.html  
└── mini-project-magazine_layout.css

## Important Rules

- Follow the required filenames exactly
- Use external CSS files
- Use CSS Grid as the primary layout method for the exercises
- You may use Flexbox inside grid items when it makes sense
- Prefer clean, readable class names
- Test thoroughly and use DevTools (Grid inspector is excellent)
- Do not copy another student’s solution
- Follow the requirements in CHECKLIST.md

## Resources

MDN – [CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids)
CSS-Tricks – [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
MDN – [grid-template-areas](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas)
Grid Garden (optional practice game) https://cssgridgarden.com/

## Before You Move On
You should be able to create a multi-column layout and a gallery without relying on floats or excessive nesting.
You should understand when Grid is a better choice than Flexbox (and vice versa).