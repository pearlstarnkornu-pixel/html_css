# 0x07 – Responsive Design

> Design once. Adapt to every screen.

## Why This Module Matters

Users browse on phones, tablets, laptops, and large monitors. A layout that only works on a desktop is incomplete. Responsive design ensures your pages remain usable, readable, and visually intentional across screen sizes.

This module teaches the core techniques: mobile-first thinking, media queries, fluid layouts, and responsive patterns for navigation, grids, and typography. These skills are required for every modern website.

You will combine everything learned so far — HTML structure, CSS foundations, Flexbox, and Grid — and make them adapt.

## Learning Goals

By the end of this module, you should be able to:

- Apply a mobile-first approach
- Write and organize media queries effectively
- Choose sensible breakpoints
- Create fluid typography and spacing
- Build responsive navigation
- Make Flexbox and Grid layouts adapt across screen sizes
- Handle images responsively
- Test layouts at multiple viewport widths

## Topics

### Mobile-First
Design for the smallest screen first, then enhance for larger screens. This keeps the base styles simple and progressive.

### Media Queries
`@media` rules let you apply CSS only when certain conditions are met (usually minimum or maximum width).

### Breakpoints
Common breakpoints target mobile, tablet, and desktop ranges. Prefer a few meaningful breakpoints over many tiny ones.

### Fluid Layouts
Use relative units (`%`, `fr`, `rem`, `em`, `vw`) and flexible containers so layouts scale naturally.

### Responsive Patterns
Navigation that adapts, card grids that reflow, images that scale, and typography that stays readable.

## What You'll Build

### Exercises

1. `0-mobile_first.html` + `0-mobile_first.css`
2. `1-media_queries.html` + `1-media_queries.css`
3. `2-responsive_nav.html` + `2-responsive_nav.css`
4. `3-responsive_cards.html` + `3-responsive_cards.css`
5. `4-fluid_typography.html` + `4-fluid_typography.css`

### Project

`mini-project-travel_site.html` + `mini-project-travel_site.css`

A complete responsive travel landing page that works well on mobile, tablet, and desktop.

## Expected Outcome

By the end of this module you should be able to:

- Build pages that look intentional on phone, tablet, and desktop
- Use media queries confidently
- Adapt Flexbox and Grid layouts across breakpoints
- Create a responsive navigation pattern
- Test and refine layouts using browser DevTools device mode

## Required Files

0x07-responsive_design/  
├── README.md  
├── CHECKLIST.md  
├── 0-mobile_first.html  
├── 0-mobile_first.css  
├── 1-media_queries.html  
├── 1-media_queries.css  
├── 2-responsive_nav.html  
├── 2-responsive_nav.css  
├── 3-responsive_cards.html  
├── 3-responsive_cards.css  
├── 4-fluid_typography.html  
├── 4-fluid_typography.css  
├── mini-project-travel_site.html  
└── mini-project-travel_site.css

Important Rules

Follow the required filenames exactly
Use external CSS files
Prefer mobile-first media queries (min-width)
Use Flexbox and/or Grid as needed
Test at multiple widths (e.g. 375px, 768px, 1024px+)
Keep code clean and readable
Do not copy another student’s solution
Follow the requirements in CHECKLIST.md

## Resources

MDN – [Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
MDN – [Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries)
MDN – [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
web.dev – [Responsive Web Design Basics](https://web.dev/responsive-web-design-basics/)

## Before You Move On
You should be able to take a desktop layout and make it work well on mobile (and vice versa) using a clear mobile-first strategy.
You should know how to test responsive behavior efficiently with DevTools.
text