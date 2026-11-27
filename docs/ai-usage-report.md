# AI Usage Report

## AI Tools Used

## Tools Used & Use Cases

**Claude** (Anthropic, Claude Sonnet 5.5) was the main AI tool for this assignment. I used it for:

- **Code review and debugging.** I gave it my Assignment 3 repository and asked what to fix to reach professional quality. It found real bugs (for example, buttons and forms that never hid because `display` in my CSS overrode the `hidden` attribute, and a crash when browser storage is blocked). I then asked it to explain each fix one by one, with the file and line, instead of rewriting my files. When my page broke, I sent it screenshots of the browser console and my code, and it helped me find the cause.

- **UI/UX and design suggestions.** It suggested how to use my favicon, a patterned background with a readability overlay, a flower logo and section icons, and listed ideas for small creative features. I chose the artwork and the design direction myself. It also explained how the rubric applies to my design choices.

- **Planning.** It turned the assignment brief into an ordered plan (repository, polish, deployment, documentation, presentation, AI declaration).

## Benefits & Challenges:

- The review found bugs I had not noticed, and explaining each one showed me why it happened, not just what to change. Reading the console error messages with its help made debugging faster. 

- The fix to make search and filter work together needed five edits that all had to be applied together. Applying only some of them crashed my project, so I decided not to use that fix and kept my original working filter. 

- I replaced `localStorage.getItem(...)` with the helper names but kept the `localStorage.` prefix, which gave the console error `localStorage.safeGet is not a function`. The error also stopped the contact form from working, because the script crashed before reaching it. Reading the console showed me the exact line.

- My images were in the wrong folder. The browser's "broken image" display and the AI's explanation of relative paths helped me fix it.

## Learning Outcomes

- Browser storage can throw errors, so access should be wrapped in `try/catch` and the page should work without it.
- The `hidden` attribute can be overridden by CSS `display` rules, and a global `[hidden] { display: none !important; }` rule is a safe fix.
- How to read the browser console and the Network tab to find a crash or a missing file.
- Why relative paths and exact file names matter on GitHub Pages, which is case-sensitive.

## Responsible Use & Modifications
Claude provided explanations, code suggestions, and code review. It did not directly edit my project files. I adapted the suggestions to my own portfolio and made decisions based on my project. I tested and reviewed the suggestions and completed my own checks of the features before submission.

| ID | Tool (model) | Date | Purpose | Files affected | What I changed and how I verified it |
|---|---|---|---|---|---|
| C01 | Claude (Sonnet 5.5) | 2026-11-22 to 2026-11-24 | Reviewed the portfolio code, explained bugs and fixes, helped debug the storage and image issues, suggested the Assignment 4 design changes, and explained deployment and documentation steps.| index.html, css/styles.css, js/script.js, assets/images/* | I applied selected changes manually and used browser previews and console messages while debugging. I did not use the combined search-and-filter rewrite. The current repository shows the design and storage changes; search-count behavior still needs improvement. |
| A01 | Claude (Sonnet 5.5) | 2026-11-23 | Generated a complete Assignment 4 code ZIP. I chose not to use the full rewrite and asked for individual fixes instead. | artifacts/202462320-sidrahsanaullah-assignment4-code.zip | I kept my own project and applied selected suggestions separately. I did not use or test the ZIP. |




Declaration

Name: Sidrah Sanaullah

Student ID: 202462320

Date: 27 November 2026

I declare that this report and the attached evidence document all of my AI use in this assignment, with complete and unedited conversations, and that I understand and can explain all the code I submitted. I understand that undeclared AI use or a false declaration will be treated as plagiarism according to KFUPM regulations.