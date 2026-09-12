# 0x00 – How the Web Works | Checklist

Complete the required work before moving to the next module.


## 1. General Requirements

Apply these requirements to every exercise.

- [ ] All required files have been created
- [ ] Filenames are exactly as specified
- [ ] Written in your own words (no copying from the internet)
- [ ] Clear and simple explanations
- [ ] Proper Markdown formatting
- [ ] Files are inside the folder `0x00-how_the_web_works`
- [ ] Work has been reviewed for accuracy


## 2. Exercise: `0-client_server.md`

### Build

- [ ] Explains what a Client is with a real-world example
- [ ] Explains what a Server is with a real-world example
- [ ] Describes how clients and servers communicate with each other
- [ ] Includes at least one real-world analogy (e.g., restaurant, library, etc.)
- [ ] Explains why the client-server model is used

### Check Your Understanding

- [ ] I can explain the client-server model to someone who doesn't know it
- [ ] I understand that my browser is a client
- [ ] I can give examples of servers I use every day

### Test

- [ ] File is properly formatted with Markdown
- [ ] Explanation is clear and easy to understand
- [ ] No obvious errors


## 3. Exercise: `1-dns_and_urls.md`

### Build

- [ ] Explains what DNS does in simple terms
- [ ] Explains why we use domain names instead of IP addresses
- [ ] Breaks down the main parts of a URL (protocol, domain, path, etc.)
- [ ] Gives a clear labeled example of a URL
- [ ] Includes a DNS analogy (e.g., phonebook, address book)

### Check Your Understanding

- [ ] I can explain DNS without using jargon
- [ ] I can identify each part of a URL
- [ ] I understand why DNS is essential for the web

### Test

- [ ] File is properly formatted with Markdown
- [ ] URL breakdown is clear and accurate
- [ ] No obvious errors


## 4. Exercise: `2-browser_rendering.md`

### Build

- [ ] Describes the main steps the browser takes after receiving HTML
- [ ] Mentions parsing, DOM building, loading resources, and rendering
- [ ] Explains why pages sometimes load in stages (not all at once)
- [ ] Includes the role of CSS and JavaScript in rendering

### Check Your Understanding

- [ ] I can explain rendering to someone who's never heard of it
- [ ] I understand why rendering happens step by step
- [ ] I can describe what happens if a resource fails to load

### Test

- [ ] File is properly formatted with Markdown
- [ ] Steps are in logical order
- [ ] No obvious errors


## 5. Exercise: `3-dom_explained.md`

### Build

- [ ] Explains what the DOM is in simple terms
- [ ] Describes the relationship between HTML and the DOM
- [ ] Mentions that JavaScript can modify the DOM
- [ ] Includes a simple analogy or example
- [ ] Explains why the DOM is useful

### Check Your Understanding

- [ ] I can explain what the DOM is without using technical jargon
- [ ] I understand the difference between HTML and the DOM
- [ ] I can give examples of DOM manipulation

### Test

- [ ] File is properly formatted with Markdown
- [ ] Explanation is clear and accessible
- [ ] No obvious errors


## 6. Exercise: `4-frontend_vs_backend.md`

### Build

- [ ] Clearly defines Frontend with examples
- [ ] Clearly defines Backend with examples
- [ ] Gives examples of what belongs to each (technologies, tasks)
- [ ] Explains how Frontend and Backend work together
- [ ] Uses a restaurant or other analogy to explain the relationship

### Check Your Understanding

- [ ] I can explain frontend vs backend to a non-developer
- [ ] I understand that frontend and backend need to communicate
- [ ] I can give examples of tasks that happen on each side

### Test

- [ ] File is properly formatted with Markdown
- [ ] Distinction between frontend and backend is clear
- [ ] No obvious errors


## 7. Exercise: `5-devtools_network.md`

### Build

- [ ] Confirms you used the Network tab in Chrome DevTools
- [ ] Describes what you see when a page loads (list of requests)
- [ ] Mentions at least 3 types of files the browser requests (HTML, CSS, JS, images, etc.)
- [ ] Explains what status code 200 means
- [ ] Briefly describes what a failed request looks like (404, 500, etc.)
- [ ] Includes a screenshot or description of what you observed

### Check Your Understanding

- [ ] I can open DevTools and find the Network tab
- [ ] I understand what the status codes mean
- [ ] I can identify when a request succeeds or fails

### Test

- [ ] File is properly formatted with Markdown
- [ ] Observations are accurate
- [ ] No obvious errors


## 8. Exercise: `6-common_misconceptions.md`

### Ensure your work

- [ ] Corrects the idea that "the website lives in the browser"
- [ ] Explains where website files actually live (on servers)
- [ ] Addresses what happens when a user is offline
- [ ] Includes at least one additional common misconception and corrects it
- [ ] Examples: "The internet is a cloud", "HTML is programming", etc.

### Check Your Understanding

- [ ] I can correct these misconceptions for others
- [ ] I understand where website files are actually stored
- [ ] I can explain what the cloud actually is

### Test

- [ ] File is properly formatted with Markdown
- [ ] Corrections are accurate and clear
- [ ] No obvious errors


## 9. Mini Project: `mini-project-journey_of_a_web_request.md`

Combine the concepts from this module into one complete explanation.

### Required Structure

- [ ] Uses a real website as an example (e.g., github.com, google.com)
- [ ] Written in clear sequential steps
- [ ] Shows real understanding (not just copied definitions)
- [ ] Includes headings or sections for each major stage

### Required Features

Describes the full journey from typing the URL to the page being visible:

- [ ] User types URL and presses Enter
- [ ] DNS lookup happens (translates domain to IP)
- [ ] Browser sends an HTTP request to the server
- [ ] Server receives and processes the request
- [ ] Server sends an HTTP response with HTML
- [ ] Browser receives and parses the HTML
- [ ] Browser builds the DOM
- [ ] Browser loads resources (CSS, JavaScript, images)
- [ ] Browser renders the page visually

### Quality Check

- [ ] Steps are in the correct order
- [ ] Each step includes enough detail to show understanding
- [ ] Real-world website example is used throughout
- [ ] Explanation is clear enough for a beginner to understand
- [ ] No copied definitions (all in your own words)

### Optional Challenge

- [ ] Include what happens if a resource fails to load (404 error)
- [ ] Mention HTTPS and what the "S" means
- [ ] Describe caching and how it speeds up subsequent visits
- [ ] Include a diagram or visual representation


## 10. Knowledge Check

Before submitting, make sure you can answer:

- [ ] What is the client-server model? (Explain it to someone)
- [ ] What does DNS do and why is it necessary?
- [ ] What are the parts of a URL?
- [ ] What happens when you type a URL and press Enter? (Step by step)
- [ ] What is the DOM and how is it different from HTML?
- [ ] What's the difference between frontend and backend?
- [ ] How can you see what files a webpage loads?
- [ ] Where do website files actually live?
- [ ] What does a 404 error mean?

You should be able to answer these without looking at your notes.


## 11. Git & Submission

Before submitting:

- [ ] All required files are present
- [ ] Work has been reviewed for accuracy
- [ ] Code (Markdown) has been checked
- [ ] Checklist is complete
- [ ] Changes have been committed
- [ ] Changes have been pushed to GitHub
- [ ] Repository link has been submitted

### Suggested Commit

git add .
git commit -m "Complete 0x00 How the Web Works module"
git push