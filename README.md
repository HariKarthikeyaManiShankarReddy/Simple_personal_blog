# Simple_personal_blog

*DESCRIPTION OF THE PROJECT*:

This project is a simple personal blog website built using HTML, CSS, and JavaScript. It is designed to showcase your basic personal information, interests, skills, and contact details in a clean and visually 

appealing format.

The website consists of structured sections like Header, About, Details, Interests, Contact, and Footer. Each section is styled using CSS for layout, color, animation, and responsiveness. The index.html file 

holds the structure, style.css manages the visual presentation, and script.js adds interactivity.

HTML Overview:
<header>: Contains the main title and subtitle of the blog.

<section class="about">: Displays your name, image, and a brief bio.

<section class="details">: Describes your education, career goals, and skills.

<section class="interests">: Lists your tech interests, hobbies, and learning goals using nested lists.

<section class="contact">: Has a button that toggles the visibility of your email.

<footer>: Displays a copyright.

JavaScript Function:

function showEmail() {
  const email = document.getElementById("email");
  email.classList.toggle("hidden");
}

This function toggles the visibility of the email paragraph. It uses:

document.getElementById() to select the paragraph.

classList.toggle("hidden") to add/remove the hidden class which controls whether the email is shown.

CSS Concepts Used:

.fade-in: Adds a fade-in effect using the @keyframes animation.

.hover: Slightly enlarges sections when hovered (transform: scale(1.02)).

@keyframes: Defines animations like fade-in and slide-down.

.hidden: Uses display: none to hide content.
