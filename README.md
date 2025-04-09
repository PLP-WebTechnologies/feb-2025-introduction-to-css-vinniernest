# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling Example</title>
    <style>
        body {
            font-family: Arial, sans-serif; /* Change the font for the whole page */
            margin: 0; /* Remove default margin */
            padding: 0; /* Remove default padding */
            background-color: #f0f0f0; /* Light background color */
        }
        header {
            background-color: #4CAF50; /* Green background for the header */
            padding: 20px; /* Padding inside the header */
            text-align: center; /* Center align the header content */
            color: white; /* White text color */
        }
        .about {
            background-color: #fff; /* White background */
            margin: 20px; /* Margin around the section */
            padding: 15px; /* Padding inside the section */
            border: 1px solid #ddd; /* Light border around the section */
            border-radius: 8px; /* Rounded corners */
        }
        #contact {
            background-color: #fff; /* White background */
            padding: 20px; /* Padding inside the section */
            margin: 20px; /* Margin outside the section */
            border: 1px solid #ddd; /* Light border around the section */
            border-radius: 8px; /* Rounded corners */
        }
        .profile-image {
            display: block; /* Make image block level */
            margin: 0 auto; /* Center the image horizontally */
            border-radius: 50%; /* Make the image circular */
            border: 3px solid #4CAF50; /* Green border around the image */
        }
        footer {
            background-color: #333; /* Dark background for the footer */
            color: white; /* White text color */
            padding: 10px; /* Padding inside the footer */
            text-align: center; /* Center align the footer content */
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Styled Page</h1>
    </header>
    <main>
        <section class="about">
            <h2>About Me</h2>
            <p>Hello, I'm a web developer learning CSS!</p>
        </section>
        <section id="contact">
            <h2>Contact Me</h2>
            <p>Email: example@example.com</p>
        </section>
        <img src="https://via.placeholder.com/150" alt="Example Image" class="profile-image">
    </main>
    <footer>
        <p>© 2025 My Website</p>
    </footer>
</body>
</html>
