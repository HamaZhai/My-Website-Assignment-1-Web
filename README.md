# Assignment 1 - HTML and CSS Basics

**Student:** Akkulov Zhasulan  
**Group:** SE-2538  
**Course:** Software Engineering, 2nd Year

## Objective

The objective of this assignment is to practise the structure and purpose of HTML, use text, lists, images, links, tables, buttons and forms, and apply basic CSS styling. The project also introduces page layout, the CSS box model and publishing a webpage with GitHub Pages.

## Project files

- `index.html` - the structure and content of the webpage.
- `style.css` - the external stylesheet with the page colours, fonts, spacing and borders.
- `photo_2026-08-23_23-50-14.jpg` - the profile image used on the webpage.
- `screenshots/` - screenshots for the report (to be added before submission).

## Part 1. Introduction to HTML

### Step 0. HTML boilerplate

Created `index.html` with `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>` and `<body>`. The page title is **My First Webpage**.

<img width="671" height="209" alt="image" src="https://github.com/user-attachments/assets/d9630ec6-9643-4f72-b665-fc7c1474c39e" />


### Step 1. Text structure

Added the student's name in an `<h1>`, the course in an `<h2>`, an About Me heading in an `<h3>`, and a personal paragraph.

<img width="414" height="92" alt="image" src="https://github.com/user-attachments/assets/7a8b4e3f-a8fd-4d24-ae82-522fe73900b7" />


### Step 2. HTML lists

Added an ordered list (`<ol>`) of hobbies and an unordered list (`<ul>`) of favourite websites.

<img width="937" height="450" alt="image" src="https://github.com/user-attachments/assets/c44e2f61-6925-42a5-935a-74333c4a9922" />


### Step 3. Images and links

Added a profile image with `<img>` and two clickable links with `<a>` to itch.io and Pinterest.

<img width="801" height="52" alt="image" src="https://github.com/user-attachments/assets/6c49a5d4-7121-4176-bf7d-17a1f7771e9d" />


### Step 4. HTML button

Added a simple **Click Me** button. It is intentionally non-functional because no functionality is required for this step.

<img width="846" height="317" alt="image" src="https://github.com/user-attachments/assets/77288a2c-e65a-4022-8b28-ba2e3b0b7886" />

## Part 2. Intermediate HTML

### Step 5. Tables

Created a weekly class schedule with the columns **Subject**, **Day** and **Time**. The schedule contains DAA and WEB classes from Monday to Saturday.

### Step 6. Tables for layout

Created a two-column layout using a table. The left column contains the menu and the right column contains the main content.

### Step 7. Emojis

Added a paragraph about today's tired mood with three emojis: 🫠 😵‍💫 😴.

### Step 8. HTML form

Created a form with:

- a Name text input;
- an Email input;
- a Favorite Color input;
- a Submit button.

The form is a front-end demonstration and does not send data to a server yet.

<img width="1766" height="1017" alt="image" src="https://github.com/user-attachments/assets/e8e25cb0-bdf1-463d-ae1c-159995758dcd" />


## Part 3. Introduction to CSS

### Step 9. Intro to CSS

Added styling to the existing HTML page using an external CSS file.

### Step 10. Inline CSS

> **Status:** To be completed. Add one inline style to a paragraph, for example `style="color: blue;"`, and update this section after taking the screenshot.

### Step 11. Internal CSS

> **Status:** To be completed. Add a small `<style>` block inside `<head>` and update this section after taking the screenshot.

### Step 12. External CSS

Created `style.css` and connected it to `index.html` with:

```html
<link rel="stylesheet" href="style.css">
```

### Step 13. CSS syntax and selectors

The stylesheet demonstrates:

- element selectors such as `body`, `h1`, `p` and `input`;
- class selectors such as `.content-box` and `.bright-button`;
- the ID selector `#header`;
- descendant selectors such as `.menu a` and `.schedule-table td`;
- the universal selector `*`.

### Step 14. Classes vs. IDs

Reusable classes are used for repeated elements such as content boxes and buttons. The unique page header uses `id="header"` and the `#header` selector.

> **Status:** The assignment rubric specifically asks for `.highlight` and `#main-heading`. These names should be added to the HTML and CSS before final submission if they are required by the instructor.

<img width="1902" height="986" alt="image" src="https://github.com/user-attachments/assets/3d05d9b6-8174-4c60-9d1d-2b7918cf4a18" />


## Part 4. Intermediate CSS

### Step 15. Favicon

> **Status:** To be completed. Add `favicon.png` and link it in the `<head>`.

### Step 16. HTML divs

> **Status:** To be completed. Add `<div>` elements for the header, main content and footer if this step is required in addition to the current semantic elements.

### Step 17. Box model

The page currently uses `margin`, `padding` and `border` on the header, menu, content boxes, image, table, form and buttons.

### Step 18. CSS positioning

The menu currently demonstrates `position: sticky`. Static, relative and absolute examples still need to be added if all three positions are required for grading.

### Step 19. CSS sizing

The page currently uses percentage and pixel units, such as `90%`, `250px` and `48px`. `em` and `rem` examples should be added if the instructor checks every listed unit.

### Step 20. Float and clear

> **Status:** To be completed. Add two simple floated boxes and a clearing element if this step is required.

### Step 21. Publish the website

> **Status:** To be completed after the GitHub repository is created. Enable GitHub Pages and add the published URL here:

`[https://[username].github.io/[repository-name]/](https://hamazhai.github.io/My-Website-Assignment-1-Web/)`

<img width="1919" height="1010" alt="image" src="https://github.com/user-attachments/assets/a9f40504-5b6a-4b12-866b-f08955cbc038" />


## Work process summary

I first created the HTML boilerplate and added personal content: headings, an About Me paragraph, hobby and website lists, a profile image, links and a button. I then added the weekly schedule, a two-column table layout, a mood paragraph with emojis and a contact form. Finally, I created an external stylesheet and applied basic CSS selectors, colours, web-safe fonts, margins, padding, borders and widths. The design uses bright colours while keeping the content separated into clear sections. The remaining advanced CSS requirements and GitHub Pages publication will be completed before the final submission.

## Final submission checklist

- [ ] Add all four screenshots to the `screenshots/` folder.
- [ ] Complete any remaining CSS steps required by the rubric.
- [ ] Create a public GitHub repository.
- [ ] Upload all project files, including `README.md`, `index.html`, `style.css`, the photo and favicon.
- [ ] Enable GitHub Pages.
- [ ] Replace the placeholder URL above with the real published URL.
