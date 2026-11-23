# Technical Documentation

## 1. Project Overview

This project is a simple personal portfolio website created using HTML, CSS, and JavaScript.

The purpose of the website is to introduce myself, show some of the projects I have worked on, list my skills, and provide a way for visitors to contact me.

The website is a static website, so it does not need a backend or database.

In Assignment 3, the website also loads live data from the GitHub API and remembers some visitor settings in the browser.

## 2. Technologies Used

HTML is used to create the structure and content of the website.

CSS is used to style the website and make it responsive.

JavaScript is used to add interactive features.

GitHub Pages can be used to host the website.

The GitHub REST API is used to load my public repositories.

The browser's localStorage is used to remember the theme and the visitor's name.

## 3. Features and How They Work

### 3.1 GitHub API
The page asks GitHub for my repositories using `fetch` and shows each one as a card with its name, description and language. It shows "Loading..." while waiting, and an error message if GitHub can't be reached.

### 3.2 Project Filter
Each project has a language label (`data-lang`). The dropdown hides the projects that don't match the language chosen. It works together with the search box.

### 3.3 Timer
The footer shows how long the visitor has been on the page, updated every second. After one minute, a thank-you message appears.

### 3.4 Visitor Name
The visitor's name is saved in the browser (`localStorage`) and shown in a welcome message. The "Not you?" button deletes it.

### 3.5 Theme
The light/dark mode choice is saved in `localStorage` and restored when the page loads.

## 4. Performance
- Images have width and height set and use lazy loading.
- Lighthouse scores [Performance]: 99

![Lighthouse scores](lighthouse-scores.png)


## 5. File Structure

The project is organized into different folders so the files are easier to manage.

```text
202462320-sidrahsanaullah-assignment3/
│
├── index.html
├── README.md
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

