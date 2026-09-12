# 0x03 – Forms & Tables

> Collect information from users and present structured data clearly.

## Why This Module Matters

Almost every useful website needs to collect information from users (login, registration, contact, search, feedback) and display structured data (pricing, schedules, comparisons, reports).

Forms and tables are fundamental building blocks of real web applications. Mastering them now means you will be able to build functional interfaces instead of only static pages.

This module builds directly on the HTML structure and semantics you learned earlier, and prepares you for styling forms and tables with CSS in later modules.

## Learning Goals

By the end of this module, you should be able to:

- Create accessible forms using proper labels and input types
- Use common form controls (text, email, password, number, select, textarea, checkbox, radio, button)
- Apply basic HTML form validation attributes
- Structure data with semantic tables (`table`, `thead`, `tbody`, `tr`, `th`, `td`)
- Combine forms and tables thoughtfully in a small project
- Explain why labels and proper table structure matter for accessibility

## Topics

### Forms
Forms allow users to send information to a website. A good form is clear, accessible, and uses the correct input type for the data being collected.

### Labels & Accessibility
Every form control should have an associated `<label>`. This helps screen reader users and also improves usability for everyone (clicking the label focuses the input).

### Common Input Types
Using the right `type` (email, password, number, date, etc.) gives better mobile keyboards, built-in validation, and clearer meaning.

### Tables
Tables are for tabular data — information that logically belongs in rows and columns. Use semantic elements so the table is understandable even without CSS.

### When to Use What
Forms collect data. Tables display structured data. Avoid using tables for page layout.

## What You'll Build

### Exercises

1. `0-contact_form.html`
2. `1-registration_form.html`
3. `2-form_controls.html`
4. `3-basic_table.html`
5. `4-structured_table.html`

### Project

`mini-project-student_portal.html`

A simple student registration + class schedule page that combines a form and a table.

## Expected Outcome

By the end of this module you should be able to:

- Build clean, accessible forms without looking up every attribute
- Create well-structured tables
- Combine forms and tables in a meaningful page
- Explain the accessibility reasons behind labels and table structure

The emphasis is on correct structure and understanding, not visual design.

## Required Files

0x03-forms_tables/  
├── README.md  
├── CHECKLIST.md  
├── 0-contact_form.html  
├── 1-registration_form.html  
├── 2-form_controls.html  
├── 3-basic_table.html  
├── 4-structured_table.html  
└── mini-project-student_portal.html

## Important Rules

- Follow the required filenames exactly
- Use clean, readable, properly indented code
- Use semantic HTML
- Every form control must have a properly associated label
- Tables must use correct structure (thead, tbody, th, etc. where appropriate)
- Test your work in the browser before submission
- Do not copy another student’s solution
- Follow the requirements in CHECKLIST.md

## Resources

MDN – [HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
MDN – [Form Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_accessibility)
MDN – [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
MDN – [HTML Table Advanced Features](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)

## Before You Move On
You should be able to explain what you built and why you made the structural choices you made.
You should not need a step-by-step tutorial to recreate a basic form or table.