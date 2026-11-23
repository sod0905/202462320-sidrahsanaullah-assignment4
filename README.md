# Personal Portfolio - Sidrah Sanaullah

This is my personal portfolio website for Assignment 3, which is an extension of the work that I have done in Assignment 1 & 2. I made it using HTML, CSS, and JavaScript, and this has slightly more advanced functionality than before, with a live GitHub API section.

## Project Description

The website is a simple portfolio where I introduce myself, show some of the projects I have worked on, list my skills, and include a contact form.

This is the third version of my portfolio.

## Sections

### About Me

A short introduction about me and my interests.

### Projects

This section shows three projects I have worked on:

- Clinic Management System - Java
- Fitness Management System - Python
- Pentomino Game - JavaFX

### Skills

A list of programming languages and technologies that I have used.

### Contact

A form where visitors can enter their name, email, and message.

## JavaScript Features

The website uses JavaScript for a few interactive features:

1. A greeting that changes depending on the time of day.
2. A dark and light mode button.
3. A menu button for smaller screens.
4. Contact form validation.
5. Smooth scrolling between sections.

## Javascript Features (Assignment 2)
1. Search projects by title, description or tags.
2. Switch between light and dark mode. The selected theme is saved.
3. Use the contact form, which checks the fields and shows a confirmation.
4. See animations when scrolling and hovering over project cards and buttons.
5. View a result count or a message when no projects match the search.

## New JavaScript Features (Assignment 3)
1. GitHub API: the "My GitHub Repositories" section loads my repositories from the GitHub API. It shows a loading message, an error message if the request fails, and a message if there are no repositories.
2. Project filter: projects can be filtered by language (All, Java, Python) and this works together with the search box.
3. Timer: the footer shows how long a visitor has been on the page, and a thank-you message appears after 25 seconds.
4. Visitor name: visitors can enter their name, which is saved in the browser. A "Not you?" button clears it.
5. Saved theme: the light/dark mode choice is remembered between visits.

## How to Run

There is nothing that needs to be installed to run the website.

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a browser.

You can also use VS Code with the Live Server extension if you have it installed.
The GitHub section requires an internet connection.

## AI Use Summary
During Assignment 3, I used ChatGPT (GPT-6) to understand the requirements and get explanations and feedback about the GitHub API section, timer, project filter, visitor-name feature, and Lighthouse. I adapted the suggestions to my project. I tested the GitHub section online and offline, and my Desktop Lighthouse Performance score was 99/100. More details are in docs/ai-usage-report.md.

## Folder Structure

```text
202462320-sidrahsanaullah-assignment3/
│
├── README.md
├── index.html
├── .gitignore
│
├── css/
│   └── styles.css
│
├── js/
│   └── script.js
│
├── assets/
│   └── images/
│
└── docs/
    ├── ai-usage-report.md
    └── technical-documentation.md