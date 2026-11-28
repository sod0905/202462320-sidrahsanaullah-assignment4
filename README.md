# Personal Portfolio - Sidrah Sanaullah

This is the final version (Assignment 4) of my personal portfolio website. I made it with HTML, CSS and JavaScript. It is a static front-end site, so it needs no backend or installation.

Live site: https://sod0905.github.io/202462320-sidrahsanaullah-assignment4/

## Project Description
The website introduces me, shows the projects I have worked on, loads my public repositories live from GitHub, lists my skills, and has a contact form. It builds on Assignments 1, 2 and 3, and in this version I focused on polish: fixing bugs, handling errors, making it responsive, and giving it a personal visual identity in relation to me.

## Sections

### Features

1. Personal greeting: changes with the time of day and uses the visitor's name once they save it ("Good evening, Sara!").
2. Dark and light mode: the choice is remembered between visits.
3. Responsive layout: works from phone to desktop, with a hamburger menu on small screens.
4. Project search and language filter for my portfolio projects.
5. Live GitHub repositories loaded from the GitHub API, with loading, empty and error messages.
6. Visitor name: saved in the browser, with a "Not you?" button to forget it.
7. Contact form with validation and clear error messages (the site has no backend, so messages are not sent).
8. Time on page timer in the footer, with a thank-you message after 25 seconds.
9. Custom visual identity: burgundy theme, patterned background with a readability overlay, flower logo, and butterfly icons before each section title.
10. Accessibility and comfort: visible focus outlines, labelled form fields, checked text contrast in both themes, and reduced-motion support for visitors who prefer less animation.

## How to Run

There is nothing that needs to be installed to run the website.

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in a browser.

You can also use VS Code with the Live Server extension if you have it installed.
The GitHub section requires an internet connection.

## How to Use the Site
1. Menu: use the links at the top to jump to a section. On a phone, tap the three-line button to open the menu.
2. Theme: press the button in the menu to switch between dark and light mode.
3. Your name: type your first name under the introduction and press Save. The greeting updates. Press "Not you?" to remove it.
4. Projects: type in the search box (for example python) or pick a language from the dropdown. Press Clear, or Escape in the box, to reset the search.
5. GitHub section: shows my repositories. If it cannot load, a message explains what happened.
6. Contact: fill in name, email and a message of at least 10 characters. Mistakes are explained under each field.

## Known Limitations

1. Contact form: It checks the fields but doesn’t send or save the message.
2. GitHub section: It needs internet. If loading fails, it shows a general error message; there’s no retry button or cached data, and repository cards don’t link to GitHub.
3. Saved name and theme: They’re stored only in that browser, so they won’t follow visitors to another device.

## AI Use Summary
I used Claude (Anthropic) as a code reviewer, debugging helper and documentation assistant: it reviewed my Assignment 3 code, explained bugs and how to fix them, helped with the design changes, and drafted documentation that I then checked against my code. I applied and tested the changes myself. The full details, the usage log and my declaration are in docs/ai-usage-report.md.

## Folder Structure

```text
202462320-sidrahsanaullah-assignment4/
│
├── assets/
│   └── images/
│       ├── background.webp
│       ├── butterfly.png
│       ├── butterfly2.png
│       ├── flower.png
│       └── project1.svg, project2.svg, project3.svg
|
├── css/
│   └── styles.css
|
├── docs/
│   ├── ai-usage-report.md
│   └── technical-documentation.md
|
├── js/
│   └── script.js
|
├── presentation/
|   ├── slides.pdf
|   └── demo-video.mp4
|
├── .gitignore
├── index.html
└── README.md
```

## Author

Sidrah Sanaullah, Software Engineering student, KFUPM. Student ID: 202462320.