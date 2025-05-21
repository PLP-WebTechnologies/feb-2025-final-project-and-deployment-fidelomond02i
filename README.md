# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.


.button {
  background-color: #4CAF50;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
  border: none;
  border-radius: 12px;
  transition: background-color 0.3s, color 0.3s;
}

.button:hover {
  background-color: #45a049;
  color: white;
}
To store data in localStorage using JavaScript, you can use the localStorage object. For example, you can store a user’s preferences like this:
function storeUserPreferences(preferences) {
  localStorage.setItem("userPreferences", JSON.stringify(preferences));
}

function getUserPreferences() {
  return JSON.parse(localStorage.getItem("userPreferences"));
}
To apply JavaScript to trigger animations, you can use event listeners. For example, you can add the following code to your JavaScript file to trigger an animation when a button is clicked:
const button = document.querySelector(".button");

button.addEventListener("click", function() {
  const preferences = getUserPreferences();
  // Do something with the user's preferences
  // For example, change the button's color
  button.style.backgroundColor = preferences.color;
});
This code will first retrieve the user’s preferences from localStorage using the getUserPreferences function. Then, it will change the button’s color based on the user’s preference. You can replace the // Do something with the user's preferences comment with your own code to perform any action you want based on the user’s preferences.
2 Minutes ago
Build a fully functional web application. Apply HTML, CSS, and JavaScript concepts learned. Deploy the project using GitHub Pages, Netlify, or Vercel.
Instructions
Choose one of the following project ideas: Blog Website: Implement a multi-page site with navigation. Ecommerce Website: Implement a multi-page site with navigation.
Note
Include at least:
A responsive design.
JavaScript interactivity.
A deployment link.
Tasks
Create a well-structured HTML5 document. Use at least 5 different HTML elements. Ensure semantic correctness.
To build a fully functional web application, you can start by creating a well-structured HTML5 document. Here’s an example of a simple blog website with navigation:
<!DOCTYPE html>
<html>
  <head>
    <title>My Blog</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <header>
      <h1>My Blog</h1>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <h2 id="home">Home</h2>
      <p>Welcome to my blog!</p>
      <h2 id="about">About</h2>
      <p>Learn more about me and my interests.</p>
      <h2 id="contact">Contact</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" />
        <label for="email">Email:</label>
        <input type="email" id="email" />
        <input type="submit" />
      </form>
    </main>
  </body>
</html>
This document includes a header with navigation, a main section with three different pages, and a form for user input. You can customize this code to fit your specific project idea.
To apply CSS and JavaScript concepts, you can add styles and interactivity to your web application. For example, you can add the following code to your styles.css file to create a responsive design:
/* Global styles */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

/* Header styles */
header {
  background-color: #333;
  color: white;
  padding: 20px;
  text-align: center;
}

/* Navigation styles */
nav {
  margin: 0 auto;
  max-width: 800px;
  display: flex;
  justify-content: center;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}

nav li {
  margin: 0 10px;
}

nav a {
  color: white;
  text-decoration: none;
}

/* Main section styles */
main {
  padding: 20px;
}

/* Form styles */
form {
  display: flex;
  flex-direction: column;
}

form label {
  margin-bottom: 5px;
}

form input {
  padding: 10px;
  margin-bottom: 10px;
}
This code adds styles to the header, navigation, main section, and form. You can customize this code to fit your specific project idea.
To add JavaScript interactivity, you can use event listeners and other JavaScript concepts. For example, you can add the following code to your script.js file to add interactivity to the form:
const form = document.querySelector("form");

form.addEventListener("submit", function(event) {
  event.preventDefault();
  const name = form.querySelector("#name").value;
  const email = form.querySelector("#email").value;
  // Do something with the form data
  // For example, send it to a server
  console.log("Form submitted with name:", name, "and email:", email);
});

Good luck and happy coding! 🚀💻
