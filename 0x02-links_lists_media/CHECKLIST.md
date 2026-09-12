# 0x02 – Links, Lists & Media | Checklist

Complete the required work before moving to the next module.


## 1. General Requirements

Apply these requirements to every exercise.

- [ ] Required files have been created
- [ ] Filenames are exactly as specified
- [ ] Code is cleanly formatted and indented
- [ ] Code is properly structured
- [ ] Valid HTML5 boilerplate is present (`<!DOCTYPE html>`, `<html lang="en">`, charset, viewport)
- [ ] Page opens correctly in the browser
- [ ] No obvious errors
- [ ] Work has been tested


## 2. Exercise: `0-links.html`

### Ensure your work

- [ ] Contains the full HTML5 boilerplate
- [ ] Contains at least one external link (to another website)
- [ ] Contains at least one internal link (to another section on the same page using `#`)
- [ ] Contains at least one email link (`mailto:`)
- [ ] All links have descriptive text (no "click here")
- [ ] At least one link opens in a new tab (`target="_blank"`) with `rel="noopener noreferrer"`
- [ ] Links are wrapped in appropriate semantic content (not just a list of random links)

### Check Your Understanding

- [ ] I can explain the difference between internal and external links
- [ ] I understand why `target="_blank"` should be used with `rel="noopener noreferrer"`
- [ ] I can explain the purpose of `mailto:` links
- [ ] I understand why descriptive link text is important for accessibility

### Test

- [ ] All links work correctly (or have clear placeholder destinations)
- [ ] Email link opens the default email client
- [ ] Internal links scroll to the correct sections
- [ ] No obvious errors


## 3. Exercise: `1-lists.html`

### Ensure your work

- [ ] Contains the full HTML5 boilerplate
- [ ] Contains an unordered list (`<ul>`) with at least 3 items
- [ ] Contains an ordered list (`<ol>`) with at least 3 items
- [ ] Contains a description list (`<dl>`) with at least 2 term/description pairs
- [ ] Lists are properly nested and indented
- [ ] Lists contain meaningful content (not just "item 1, item 2")

### Check Your Understanding

- [ ] I can explain when to use an unordered list vs an ordered list
- [ ] I understand the structure of a description list (`<dl>`, `<dt>`, `<dd>`)
- [ ] I can explain why lists should be properly indented

### Test

- [ ] Lists display correctly in browser
- [ ] Bullet points or numbers appear appropriately
- [ ] Description list shows terms and descriptions clearly
- [ ] No obvious errors


## 4. Exercise: `2-images.html`

### Ensure your work

- [ ] Contains the full HTML5 boilerplate
- [ ] Contains at least two images
- [ ] Every image has a meaningful `alt` attribute (describes the image content)
- [ ] Uses a relative path for at least one image (image file in same or nearby folder)
- [ ] Uses an absolute URL for at least one image (image from another website)
- [ ] Images display correctly in the browser
- [ ] Uses appropriate `width` and `height` attributes (optional but recommended)

### Check Your Understanding

- [ ] I can explain the difference between relative and absolute paths
- [ ] I understand why `alt` text is required for images
- [ ] I can explain what makes a good `alt` description vs a bad one
- [ ] I understand when to use relative paths vs absolute URLs

### Test

- [ ] All images display correctly
- [ ] Alt text appears when images fail to load
- [ ] Relative path image works with the project structure
- [ ] Absolute URL image works with an external source
- [ ] No obvious errors


## 5. Exercise: `3-navigation.html`

### Ensure your work

- [ ] Contains the full HTML5 boilerplate
- [ ] Contains a `<nav>` element for the navigation menu
- [ ] Navigation has at least 4 links
- [ ] Links point to different sections of the page using ID attributes (`#section-id`)
- [ ] Page has matching sections with corresponding `id` attributes
- [ ] Each section has meaningful content (not just placeholder text)
- [ ] Uses heading hierarchy (h1 for page title, h2 for sections)

### Check Your Understanding

- [ ] I can explain why the `<nav>` element is semantic
- [ ] I understand how anchor links work with ID attributes
- [ ] I can explain why navigation should be clear and descriptive

### Test

- [ ] Navigation links scroll to correct sections
- [ ] Each section is visible with clear content
- [ ] No obvious errors


## 6. Exercise: `4-figures.html`

### Ensure your work

- [ ] Contains the full HTML5 boilerplate
- [ ] Contains at least two `<figure>` elements
- [ ] Each figure includes an image (`<img>`)
- [ ] Each figure includes a `<figcaption>` with descriptive text
- [ ] Captions are meaningful and explain the image content
- [ ] Images have proper `alt` text
- [ ] Figures are used appropriately (not just decorative images)

### Check Your Understanding

- [ ] I can explain the purpose of the `<figure>` element
- [ ] I understand the relationship between `<figure>` and `<figcaption>`
- [ ] I can explain how figures differ from just using an image tag

### Test

- [ ] Figures display correctly with images and captions
- [ ] Captions are clearly associated with the correct images
- [ ] No obvious errors


## 7. Mini Project: `mini-project-restaurant.html`

Combine the concepts from this module into one complete restaurant homepage.

### Required Structure

- [ ] Correct HTML5 boilerplate with appropriate `<title>`
- [ ] Uses semantic structure:
  - [ ] `<header>` for restaurant name/logo
  - [ ] `<nav>` for navigation menu
  - [ ] `<main>` for main content
  - [ ] `<section>` for each content area
  - [ ] `<footer>` with contact information

### Required Features

- [ ] Navigation menu with at least 4 links (e.g., Home, Menu, About, Contact)
- [ ] At least one unordered or ordered list (e.g., menu items, features)
- [ ] At least two images with proper `alt` text
- [ ] Uses at least one `<figure>` with a caption
- [ ] Has multiple sections (e.g., About, Menu, Location, Contact, Specials)
- [ ] Contains at least one link (external or email)

### Quality Check

- [ ] Code is readable and properly indented
- [ ] Structure is appropriate and semantic
- [ ] Looks like a complete, realistic restaurant homepage
- [ ] Content is meaningful (not just placeholder text)
- [ ] No obvious errors

### Optional Challenge

- [ ] Add a description list with menu descriptions (dish name + description)
- [ ] Include an ordered list for a "Top Rated" or "Most Popular" section
- [ ] Add internal links that scroll to specific sections
- [ ] Create a contact section with an email link



## 8. Knowledge Check

Before submitting, make sure you can answer:

- [ ] What is the difference between internal and external links?
- [ ] Why is `alt` text important for images?
- [ ] When should you use an unordered list vs an ordered list?
- [ ] What is a description list and when would you use it?
- [ ] What is the difference between relative and absolute paths?
- [ ] Why is the `<figure>` element useful?
- [ ] What is the purpose of the `<nav>` element?

You should be able to answer these without simply copying from your code.


## 9. Git & Submission

Before submitting check:

- [ ] All required files are present
- [ ] Work has been tested in the browser
- [ ] Code has been reviewed
- [ ] Checklist is complete
- [ ] Changes have been committed
- [ ] Changes have been pushed to GitHub
- [ ] Project is ready for review

### Suggested Commit

git add .
git commit -m "Complete 0x02 Links, Lists & Media module"
git push