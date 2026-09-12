# 0x07 – Responsive Design | Checklist

Complete the required work before moving to the next module.


## 1. General Requirements

- [ ] All required files have been created
- [ ] Filenames are exactly as specified
- [ ] HTML files correctly link to their CSS files
- [ ] Code is cleanly formatted
- [ ] Layouts tested at multiple viewport widths
- [ ] Mobile-first approach used where required
- [ ] Work has been tested in the browser / DevTools device mode


## 2. Exercise: `0-mobile_first.html` + `0-mobile_first.css`

### Ensure your work
- [ ] Base styles target small screens
- [ ] Uses at least one `min-width` media query to enhance for larger screens
- [ ] Layout clearly changes between mobile and larger viewports
- [ ] Demonstrates mobile-first thinking

### Check Your Understanding
- [ ] I can explain what mobile-first means
- [ ] I understand why `min-width` media queries fit a mobile-first approach

### Test
- [ ] Looks good on a narrow screen
- [ ] Improves on a wider screen
- [ ] Tested in DevTools device mode


## 3. Exercise: `1-media_queries.html` + `1-media_queries.css`

### Ensure your work
- [ ] Uses at least two breakpoints
- [ ] Changes layout, spacing, or typography across breakpoints
- [ ] Media queries are organized and readable
- [ ] Visual differences between breakpoints are clear

### Check Your Understanding
- [ ] I can write a basic `@media (min-width: …)` rule
- [ ] I understand the purpose of breakpoints

### Test
- [ ] Styles apply at the correct widths
- [ ] Tested at multiple widths


## 4. Exercise: `2-responsive_nav.html` + `2-responsive_nav.css`

### Ensure your work
- [ ] Navigation works on mobile (stacked or simplified)
- [ ] Navigation adapts on larger screens (horizontal bar)
- [ ] Uses Flexbox (and media queries) appropriately
- [ ] Links remain usable at all sizes

### Check Your Understanding
- [ ] I can adapt a navbar across breakpoints
- [ ] I understand common responsive navigation patterns

### Test
- [ ] Mobile nav is usable
- [ ] Desktop nav looks intentional
- [ ] Tested at multiple widths


## 5. Exercise: `3-responsive_cards.html` + `3-responsive_cards.css`

### Ensure your work
- [ ] Cards stack on small screens
- [ ] Cards move into multiple columns on larger screens
- [ ] Uses Flexbox or Grid + media queries
- [ ] Spacing remains consistent across breakpoints

### Check Your Understanding
- [ ] I can make a card layout reflow responsively
- [ ] I know how to combine Grid/Flexbox with media queries

### Test
- [ ] One column on mobile
- [ ] Multi-column on tablet/desktop
- [ ] Tested at multiple widths


## 6. Exercise: `4-fluid_typography.html` + `4-fluid_typography.css`

### Ensure your work
- [ ] Typography scales across screen sizes
- [ ] Line length remains readable
- [ ] Spacing feels balanced on small and large screens
- [ ] Headings and body text maintain hierarchy

### Check Your Understanding
- [ ] I understand why fixed `px` sizes can be limiting
- [ ] I can adjust type and spacing responsively

### Test
- [ ] Text remains readable on mobile and desktop
- [ ] Tested at multiple widths


## 7. Project: `mini-project-travel_site.html` + `.css`

### Required Structure
- [ ] Semantic HTML
- [ ] External CSS file
- [ ] Header with navigation
- [ ] Hero / intro section
- [ ] Features or destination cards section
- [ ] Footer

### Required Responsive Behavior
- [ ] Mobile-first base styles
- [ ] Navigation adapts across breakpoints
- [ ] Card/feature section reflows (stack → columns)
- [ ] Typography and spacing adjust appropriately
- [ ] Images scale correctly
- [ ] Page feels intentional at ~375px, ~768px, and ~1024px+

### Quality Check
- [ ] CSS is organized (base styles first, then media queries)
- [ ] No major horizontal scrolling on mobile
- [ ] Layout does not look broken at common widths
- [ ] Project feels complete for this level

### Optional Challenge
- [ ] Add a third breakpoint for large desktops
- [ ] Improve the mobile navigation pattern further
- [ ] Use `clamp()` for fluid typography


## 8. Knowledge Check

- [ ] What does “mobile-first” mean in practice?
- [ ] Why do we often prefer `min-width` media queries?
- [ ] What is a breakpoint?
- [ ] How do you make a Grid/Flexbox card layout responsive?
- [ ] How do you test responsive layouts efficiently?


## 9. Git & Submission

- [ ] All required files are present
- [ ] HTML files correctly link to CSS files
- [ ] Work has been tested at multiple widths
- [ ] Checklist is complete
- [ ] Changes committed and pushed
- [ ] Ready for review

### Suggested Commit

git add .
git commit -m "Complete 0x07-responsive_design"
git push