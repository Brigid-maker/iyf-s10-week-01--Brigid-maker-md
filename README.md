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

<!-- box-model-practice.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Box Model Practice</title>
  <style>
    /* Exercise 1: Box Model Visualization */
    .box {
      width: 100px;
      height: 100px;
      background-color: lightblue; /* content */
      padding: 20px; /* padding */
      border: 5px solid black; /* border */
      margin: 10px; /* margin */
      display: inline-block;
    }

    /* Exercise 2: Debug the Layout */
    .broken-box {
      width: 300px;
      padding: 20px;
      border: none;
      box-sizing: border-box;
      background-color: lightgreen;
      margin: 10px;
    }

    /* Exercise 3: Card Component */
    .card {
      width: 300px;
      padding: 20px;
      border: 1px solid gray;
    }
    
    .card img {
      width: 100%;
      height: auto;
      display: block;
    }
    
    .title {
      margin-top: 20px;
      margin-bottom: 15px;
    }
    
    .btn {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <!-- Exercise 1: Box Model Visualization -->
  <h2>Box Model Visualization</h2>
  <div class="box">Box 1</div>
  <div class="box">Box 2</div>
  <div class="box">Box 3</div>
  <div class="box">Box 4</div>

  <!-- Exercise 2: Debug the Layout -->
  <h2>Debugged Box</h2>
  <div class="broken-box">This box is 300px wide (including padding)</div>

  <!-- Exercise 3: Card Component -->
  <h2>Card Component</h2>
  <div class="card">
    <img src="https:                                            
    <h2 class="title">Card Title</h2>
    <p>This is a card description.</p>
    <button class="btn">Click Me</button>
  </div>
</body>
</html>


