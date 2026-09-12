# 0x01 – HTML Foundations | Checklist

Complete the required work before moving to the next module.


## 1. General Requirements

Apply these requirements to every exercise.

- [ ] Required files have been created
- [ ] Filenames are exactly as specified
- [ ] Code is cleanly formatted and indented
- [ ] Code is properly structured
- [ ] Valid HTML5 boilerplate is present
- [ ] Page opens correctly in the browser
- [ ] No obvious errors
- [ ] Work has been tested


## 2. Exercise: `0-boilerplate.html`

### Ensure your work

- [ ] Contains `<!DOCTYPE html>`
- [ ] Has `<html lang="en">`
- [ ] Has `<head>` with `<meta charset="UTF-8">`
- [ ] Has viewport meta tag (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`)
- [ ] Has a meaningful `<title>`
- [ ] Has `<body>` with at least one heading (`<h1>`)
- [ ] Has `<body>` with at least one paragraph (`<p>`)

### Check Your Understanding

- [ ] I can explain what `<!DOCTYPE html>` does
- [ ] I can explain why `lang="en"` is important
- [ ] I can explain the purpose of the viewport meta tag

### Test

- [ ] File opens in browser
- [ ] Title appears correctly in the browser tab
- [ ] Heading and paragraph are visible
- [ ] No obvious errors


## 3. Exercise: `1-headings.html`

### Ensure your work

- [ ] Contains the full HTML5 boilerplate
- [ ] Has one `<h1>` heading
- [ ] Has at least two `<h2>` headings
- [ ] Has at least two `<h3>` headings
- [ ] Heading levels follow a logical order (no skipping from h1 to h4)
- [ ] Each heading has meaningful content

### Check Your Understanding

- [ ] I can explain why heading hierarchy matters
- [ ] I can explain what happens when you skip heading levels
- [ ] I understand when to use h1 vs h2 vs h3

### Test

- [ ] Headings display correctly in browser
- [ ] Hierarchy is visually clear
- [ ] No obvious errors


## 4. Exercise: `2-text_formatting.html`

### Ensure your work

- [ ] Contains the full HTML5 boilerplate
- [ ] Uses at least three different text formatting tags
  - [ ] e.g., `<strong>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, `<sup>`, etc.
- [ ] Contains a paragraph that mixes normal text with formatted text
- [ ] Code is properly nested
- [ ] Formatting is used appropriately (not just random)

### Check Your Understanding

- [ ] I can explain the difference between `<strong>` and `<em>`
- [ ] I can explain when to use `<mark>` vs other formatting tags
- [ ] I understand the purpose of inline text formatting

### Test

- [ ] Text formatting displays correctly in browser
- [ ] No broken markup
- [ ] No obvious errors


## 5. Exercise: `3-semantic_page.html`

### Ensure your work

- [ ] Contains the full HTML5 boilerplate
- [ ] Uses `<header>` for the page header
- [ ] Uses `<main>` for the main content
- [ ] Uses at least one `<section>` or `<article>`
- [ ] Uses `<footer>` for the page footer
- [ ] Page has clear structure and enough content to look complete
- [ ] Content is meaningful (not just placeholder text)

### Check Your Understanding

- [ ] I can explain the difference between `<header>` and `<head>`
- [ ] I can explain when to use `<section>` vs `<article>`
- [ ] I understand why semantic elements are better than using `<div>` everywhere

### Test

- [ ] All semantic elements display correctly
- [ ] Page has a clear visual structure
- [ ] No obvious errors


## 6. Exercise: `4-accessibility_basics.html`

### Ensure your work

- [ ] Contains the full HTML5 boilerplate
- [ ] Uses proper heading hierarchy (h1 → h2 → h3)
- [ ] Contains at least one image with a meaningful `alt` attribute
- [ ] Sets the page language with `lang="en"`
- [ ] Contains at least one descriptive link (not "click here")
- [ ] Shows basic awareness of accessibility good practices
- [ ] Uses semantic HTML where possible

### Check Your Understanding

- [ ] I can explain why `alt` text is important
- [ ] I can explain what makes a good link description
- [ ] I can explain why heading hierarchy helps accessibility
- [ ] I understand who benefits from accessible HTML

### Test

- [ ] Image with alt text displays
- [ ] Link text is descriptive and makes sense out of context
- [ ] No obvious errors
- [ ] Page passes basic accessibility checks (e.g., WAVE or Lighthouse)


## 7. Exercise: `5-blog_article.html`

### Ensure your work

- [ ] Contains the full HTML5 boilerplate
- [ ] Content is wrapped in an `<article>` element
- [ ] Has a clear title using `<h1>`
- [ ] Includes author or date information (using appropriate HTML)
- [ ] Uses at least two subheadings (`<h2>`)
- [ ] Contains multiple paragraphs of real content
- [ ] Uses semantic structure (`<header>`, `<footer>` inside the article recommended)
- [ ] Content is substantial and well-organized

### Check Your Understanding

- [ ] I can explain why `<article>` is appropriate for a blog post
- [ ] I can explain the difference between `<article>` and `<section>`
- [ ] I understand how to structure longer content

### Test

- [ ] Article displays as a complete blog post
- [ ] Structure is clear and logical
- [ ] No obvious errors



## 8. Mini Project: `mini-project-profile_page.html`

Combine the concepts from this module.

### Required Structure

- [ ] Correct HTML5 boilerplate with appropriate `<title>`
- [ ] Uses semantic elements (`<header>`, `<main>`, `<section>`, `<footer>`)
- [ ] Clear heading hierarchy (h1 for name/title, h2 for sections)

### Required Features

- [ ] Clear main heading (name or title)
- [ ] Contains multiple content sections:
  - [ ] About/Introduction
  - [ ] Skills or Experience
  - [ ] Interests or Hobbies
  - [ ] Contact or Social links
  - [ ] At least one additional section of your choice
- [ ] Includes at least one image with proper `alt` text
- [ ] Uses appropriate text formatting within the content
- [ ] Contains at least one descriptive link
- [ ] Looks like a complete, well-structured personal profile page

### Quality Check

- [ ] Code is readable and properly indented
- [ ] Structure is appropriate and semantic
- [ ] No broken links/assets
- [ ] No obvious errors
- [ ] Project feels complete and professional

### Optional Challenge

- [ ] Add a `<nav>` element with navigation links
- [ ] Include an `<aside>` element with additional content
- [ ] Add a quote or testimonial using `<blockquote>`



## 9. Knowledge Check

Before submitting, make sure you can answer:

- [ ] What is the purpose of the HTML5 doctype?
- [ ] Why is semantic HTML important?
- [ ] How do you properly structure headings on a page?
- [ ] What makes HTML accessible?
- [ ] When would you use `<section>` instead of `<div>`?
- [ ] Why is `alt` text important for images?
- [ ] What is the difference between `<header>` and `<head>`?

You should be able to answer these without simply copying from your code.



## 10. Git & Submission

Before submitting:

- [ ] All required files are present
- [ ] Work has been tested in the browser
- [ ] Code has been reviewed
- [ ] Checklist is complete
- [ ] Changes have been committed
- [ ] Changes have been pushed to GitHub
- [ ] Project is ready for review

### Suggested Commit

git add .
git commit -m "Complete 0x01 HTML Foundations module"
git push