# Week 01: Personal Web Portfolio

## Author
- **Name:** Cheryl Adhiambo
- **GitHub:** https://github.com/Brigid-maker 
- **Date:** March 6, 2026

## Project Description
This project is a simple multi-page personal web portfolio created using HTML. The goal of the project is to practice web development basics such as creating web pages, structuring content using semantic HTML, linking pages together, and building a contact form.

The portfolio includes a home page, an about page, a projects page, and a contact page.

## Technologies Used
- HTML5

## Features
- Multi-page website structure
- Navigation menu linking all pages
- About page describing the author
- Projects page showing sample work
- Contact page with a functional form

## How to Run
1. Clone this repository
2. Open the project folder
3. Open `index.html` in any web browser

## Lessons Learned
While building this project, I learned how to:
- Create multiple HTML files
- Use semantic HTML elements
- Link pages using navigation menus
- Create forms using labels, inputs, and validation

## Challenges Faced
One challenge I faced was organizing multiple pages and ensuring the navigation links worked correctly. I solved this by checking the file names and ensuring all pages were connected properly.

Another challenge was creating a structured contact form with proper labels and input validation.

## Screenshots
Screenshots can be added here if needed.

## Live Demo
Not deployed yet.

/* ===============================
   RESET (Task 3.1)
================================ */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* ===============================
   COLOR SYSTEM (Task 3.4)
================================ */
:root {
    --color-primary: #2563eb;
    --color-secondary: #9333ea;
    --color-background: #f9fafb;
    --color-text: #1f2937;
    --color-muted: #6b7280;

    --color-primary-light: #60a5fa;
    --color-primary-dark: #1e40af;

    /* TYPOGRAPHY SCALE (Task 3.3) */
    --font-xs: 0.75rem;
    --font-sm: 0.875rem;
    --font-base: 1rem;
    --font-lg: 1.125rem;
    --font-xl: 1.25rem;
    --font-2xl: 1.5rem;
    --font-3xl: 1.875rem;
    --font-4xl: 2.25rem;
}

/* ===============================
   BASE TYPOGRAPHY (Task 3.1)
================================ */
body {
    font-family: 'Open Sans', sans-serif;
    font-size: 16px;
    line-height: 1.6;
    background-color: var(--color-background);
    color: var(--color-text);
    padding: 20px;
}

/* Headings */
h1, h2, h3, h4, h5, h6 {
    font-family: 'Poppins', sans-serif;
    margin-bottom: 10px;
}

h1 {
    font-size: var(--font-4xl);
    font-weight: 700;
    color: var(--color-primary);
}

h2 {
    font-size: var(--font-3xl);
    font-weight: 600;
}

h3 {
    font-size: var(--font-2xl);
    font-weight: 600;
}

h4 { font-size: var(--font-xl); }
h5 { font-size: var(--font-lg); }
h6 { font-size: var(--font-base); }

/* Paragraph */
p {
    margin-bottom: 15px;
}

/* ===============================
   LINKS & BUTTONS
================================ */
a {
    color: var(--color-primary);
    text-decoration: none;
}

a:hover {
    color: var(--color-primary-dark);
    text-decoration: underline;
}

button {
    background-color: var(--color-primary);
    color: white;
    border: none;
    padding: 10px 15px;
    cursor: pointer;
}

button:hover {
    background-color: var(--color-primary-dark);
}

/* ===============================
   LAYOUT
================================ */
.container {
    max-width: 800px;
    margin: 0 auto;
}

section {
    margin-bottom: 40px;
}

/* ===============================
   BOX MODEL (Task 3.2)
================================ */
.box {
    width: 300px;
    padding: 20px;
    border: 2px solid black;
    margin: 20px auto;
    background-color: lightblue;
}

/* FIXED BOX */
.broken-box {
    width: 300px;
    padding: 20px;
    border: 2px solid red;
    margin: 20px auto;
    box-sizing: border-box; /* FIX */
    background-color: lightcoral;
}

/* ===============================
   CARD COMPONENT
================================ */
.card {
    width: 300px;
    padding: 20px;
    border: 1px solid gray;
    margin: 20px auto;
}

.card img {
    width: 100%;
    margin-bottom: 10px;
}

.card h3 {
    margin-bottom: 15px;
}

.card p {
    margin-bottom: 15px;
}
