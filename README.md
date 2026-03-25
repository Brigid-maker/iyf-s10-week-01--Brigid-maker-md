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


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box Model Practice</title>

    <style>
        /* ========================= */
        /* RESET & BASE STYLING      */
        /* ========================= */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box; /* Includes padding and border in total width */
        }

        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        h1 {
            margin-bottom: 30px;
        }

        h2 {
            margin-top: 40px;
            margin-bottom: 15px;
        }

        /* ========================= */
        /* EXERCISE 1: BOX MODEL VISUALIZATION */
        /* ========================= */
        .box {
            width: 200px;               /* Content width */
            padding: 20px;              /* Padding inside */
            border: 5px solid blue;     /* Border */
            margin: 20px;               /* Margin outside */
            background-color: lightblue; /* Content color */
        }

        .box2 { background-color: lightgreen; }
        .box3 { background-color: lightcoral; }
        .box4 { background-color: lightgoldenrodyellow; }

        /* ========================= */
        /* EXERCISE 2: DEBUG FIXED BOX */
        /* ========================= */
        .broken-box {
            width: 300px;               /* Total width */
            padding: 20px;              /* Padding */
            border: none;               /* No border */
            box-sizing: border-box;     /* Fix: width includes padding */
            background-color: lightgray;
            margin: 20px 0;
        }

        /* ========================= */
        /* EXERCISE 3: CARD COMPONENT */
        /* ========================= */
        .card {
            width: 300px;               /* Total card width */
            border: 1px solid gray;     /* Border */
            margin-top: 20px;
            box-sizing: border-box;     /* Include padding in width */
        }

        .card img {
            width: 100%;                /* Image fills the card width */
            display: block;
        }

        .card-content {
            padding: 20px;              /* Padding inside card */
        }

        .card-content h2 {
            margin-bottom: 15px;        /* Title spacing */
        }

        .card-content p {
            margin-bottom: 15px;        /* Description spacing */
        }

        .card-content button {
            padding: 10px 15px;         /* Button padding */
            border: none;
            background-color: blue;
            color: white;
            cursor: pointer;
        }

        .card-content button:hover {
            background-color: darkblue;
        }
    </style>
</head>
<body>

    <h1>Box Model Practice</h1>

    <!-- ========================= -->
    <!-- EXERCISE 1: BOX MODEL VISUALIZATION -->
    <!-- ========================= -->
    <h2>Exercise 1: Box Model Visualization</h2>
    <div class="box">
        Box 1 <br>
        Content: light blue area<br>
        Padding: space inside box<br>
        Border: blue outline<br>
        Margin: space outside
    </div>
    <div class="box box2">Box 2</div>
    <div class="box box3">Box 3</div>
    <div class="box box4">Box 4</div>

    <!-- ========================= -->
    <!-- EXERCISE 2: DEBUG FIXED BOX -->
    <!-- ========================= -->
    <h2>Exercise 2: Debug the Layout</h2>
    <div class="broken-box">
        This box is exactly 300px wide using <code>box-sizing: border-box</code>.
    </div>

    <!-- ========================= -->
    <!-- EXERCISE 3: CARD COMPONENT -->
    <!-- ========================= -->
    <h2>Exercise 3: Card Component</h2>
    <div class="card">
        <img src="https://via.placeholder.com/300x150" alt="Card Image">

        <div class="card-content">
            <h2>Card Title</h2>
            <p>This is the card description text. Padding creates spacing inside the card, border outlines it, and margin separates the card from other elements.</p>
            <button>Read More</button>
        </div>
    </div>

</body>
</html>

