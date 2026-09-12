# 0x00 – How the Web Works

> Before you write a single line of HTML, you must understand what happens when a user types a URL and presses Enter.

This module gives you the essential mental model for everything that follows in web development. By the end, you will understand the full journey of a web request and how browsers turn code into pages.

## Why This Module Matters

Understanding how the web works is the foundation of all web development. Without this knowledge, you're just memorizing syntax without understanding the context. Every HTML tag you write, every CSS rule you apply, and every JavaScript function you create exists within this larger system.

This module establishes the mental model you'll use throughout your entire development career. It connects directly to HTML (where does the HTML come from?), CSS (how does the browser apply styles?), and JavaScript (how does JS interact with the DOM?). You'll also understand what happens when things go wrong and how to debug effectively.

## Learning Goals

By the end of this module, you should be able to:

- [ ] Explain the Client–Server model clearly with a real-world analogy
- [ ] Understand IP, TCP/IP, and DNS at a practical level
- [ ] Break down the parts of a URL and explain what each part does
- [ ] Describe how browsers request and render pages step by step
- [ ] Explain what the DOM is and why it matters
- [ ] Distinguish Frontend from Backend and explain how they work together
- [ ] Use Chrome DevTools (Elements + Network tabs) to inspect web pages
- [ ] Correct common beginner misconceptions about how the web works

## Topics

### Client–Server Model

The foundation of the web. You'll learn what clients and servers are, how they communicate, and why this model works so well for the internet.

### IP Addresses & TCP/IP

Computers need addresses just like houses. You'll learn how devices find each other on the internet and how data travels from one computer to another.

### DNS

The internet's phone book. You'll learn how domain names (like google.com) get translated into IP addresses that computers can understand.

### Understanding URLs

Every link you've ever clicked has a structure. You'll break down URLs into their parts: protocol, domain, path, query parameters, and fragments.

### How Browsers Request Pages

Browsers don't just magically show pages. You'll learn the HTTP request/response cycle and what actually happens when you press Enter in the address bar.

### How Browsers Render Pages

HTML, CSS, and JavaScript arrive as text. You'll learn how browsers convert these into the visual pages you see on screen.

### The DOM

The Document Object Model is how browsers represent web pages in memory. You'll learn what it is, why it exists, and how it enables interactivity.

### Frontend vs Backend

Two sides of web development. You'll learn what each does, what languages and tools are used, and how they work together.

### Chrome DevTools

Developer tools are your best friend. You'll learn to use the Network tab to see requests and responses, and the Elements tab to inspect the DOM.

### Common Misconceptions

Many beginners have wrong ideas about how the web works. We'll identify and correct the most common ones.

## What You'll Build

You will complete:

### Exercises

1. `0-client_server.md` - Explain the client-server model
2. `1-dns_and_urls.md` - Break down DNS and URLs
3. `2-browser_rendering.md` - Describe browser rendering steps
4. `3-dom_explained.md` - Explain the DOM in your own words
5. `4-frontend_vs_backend.md` - Distinguish frontend and backend
6. `5-devtools_network.md` - Analyze network requests
7. `6-common_misconceptions.md` - Correct beginner misconceptions

### Mini Project

`mini-project-journey_of_a_web_request.md`

Write the complete story of what happens when a user visits a website, combining all the concepts from this module into one clear, sequential explanation.

## Expected Outcome

By the end of this module, you should be able to:

- Explain the entire web request journey from URL to rendered page
- Identify the role of each technology in the web stack
- Use DevTools to inspect network traffic and the DOM
- Distinguish between concepts you previously mixed up
- Build a clear mental model that helps you understand everything else you learn

The emphasis is on understanding the big picture, not memorizing technical details.

## Required Files

0x00-how_the_web_works/  
├── README.md  
├── CHECKLIST.md  
├── 0-client_server.md  
├── 1-dns_and_urls.md  
├── 2-browser_rendering.md  
├── 3-dom_explained.md  
├── 4-frontend_vs_backend.md  
├── 5-devtools_network.md  
├── 6-common_misconceptions.md  
└── mini-project-journey_of_a_web_request.md

## Important Rules

- Write in your own words (do not copy from the internet)
- Keep explanations clear and simple
- Use proper Markdown formatting
- Focus on understanding, not length
- Include real-world analogies to help explain concepts
- Test your understanding by explaining to someone else
- Do not copy another student's work
- Follow the requirements in CHECKLIST.md

## Resources

- [MDN – How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- [MDN – What is a URL?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_URL)
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/)

## Before You Move On

- You should be able to explain:
- What happens when you type a URL and press Enter (step by step)
- The difference between frontend and backend
- What DNS does and why we need it
- How the browser turns HTML into a visual page
- What the DOM is and how it relates to HTML
- How to use the Network tab in DevTools to see what files are loaded
- You should not need a step-by-step tutorial to explain how the web works.

## Special Note

This module is conceptual — you're not writing code. But this conceptual knowledge is more important than any single syntax you'll learn. The best developers understand the system, not just the syntax.