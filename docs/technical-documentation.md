# Technical Documentation

## 1. Project Overview

This project is a simple static personal portfolio website created using HTML, CSS, and JavaScript.

The purpose of the website is to introduce myself, show some of the projects I have worked on, list my skills, and provide a way for visitors to contact me.

The website is a static website, so it does not need a backend or database. The website also loads live data from the GitHub API and remembers some visitor settings in the browser.

## 2. Architecture and Files


| File | Responsibility |
|---|---|
| `index.html` | Page structure, navigation, project cards, skills, repository section, visitor form, contact form, and footer. Loads the CSS and deferred JavaScript. |
| `css/styles.css` | Color variables, dark/light theme styling, cards, forms, responsive layout, focus treatment, hover effects, and reduced-motion rules. |
| `js/script.js` | Greeting, theme, mobile menu, contact validation, search, reveal effects, GitHub API request, page timer, language filter, and visitor-name storage. |
| `assets/images/` | Three project-preview SVGs in the checked-in source. The flower, background, and favicon assets discussed for Assignment 4 are not in the public snapshot. |
| `docs/ai-usage-report.md` | AI-use narrative, usage log, declaration template, and evidence status. |
| `assets/images/background.webp`	| Decorative page background. |
| `assets/images/flower.png` |	Brand image and browser favicon source. |
| `assets/images/butterfly2.png` | Decorative icon before section headings. |
| `assets/images/butterfly.png` |	Favicon image. |
| `assets/images/project1.svg–project3.svg` |	Project-card preview images. |
| `docs/technical-documentation.md` | This file. |

## 3. Features and How They Work
### 3.1 Layout and design
The page adjusts to fit different screen sizes. On small screens, the navigation links are replaced by a menu button. The background image has a color layer to help keep the text readable. Butterfly pictures appear beside the section headings.

### 3.2 Theme switch
Use the button to switch between dark and light mode. The website remembers your choice for your next visit. It uses dark mode if you have not chosen a theme before.

### 3.3 Greeting and visitor name
The greeting changes with the time of day. If a visitor saves their name, it appears in the greeting. Saving or removing the name updates the greeting without refreshing the page.

### 3.4 Mobile menu
Tap the menu button to show or hide the links. Choosing a link closes the menu.

### 3.5 Project search and language filter
Search for words in the project cards or choose a language from the dropdown. When you use both controls, the cards hide correctly, but the result count may not match the cards still showing.

### 3.6 GitHub repositories
The website gets public repositories from GitHub and shows each repository’s name, description, and main language. It shows a message while loading, if no repositories are found, or if something goes wrong. This feature needs internet access.

### 3.7 Contact form
The form checks that the name, email, and message are filled in correctly. It does not send or save the message; it tells the visitor this after they submit it.
 
### 3.8 Time counter
The timer starts when the page opens and updates every second. A thank-you message appears after 25 seconds. Reloading the page resets the timer.

### 3.9 Accessibility
Form fields have labels, keyboard focus is outlined, and images have descriptions for screen readers. The site reduces animation for people who prefer less motion. The butterflies are decorative; the section headings still name each section.


## 4. File Structure

The project is organized into different folders so the files are easier to manage.

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


