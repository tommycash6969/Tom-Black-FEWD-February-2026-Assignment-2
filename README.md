# Tom-Black-FEWD-February-2026
Tom Black FEWD-February-2026- Assignment 2
<br>
Repository includes index.html and README.md and Images and Video folders respectively.
# FreeLivingDesigns Portfolio - README

## Overview
This project is a personal portfolio webpage built as a single static HTML file: `index.html`.

The page introduces Tom Black as a front-end web designer and includes:
- A logo and header section
    I included the logo of my business FreeLivingDesigns as an image using image source folder Images with respective file logo.png
- An About Me section
    A short introduction of myslef with an emphasis on my WordPress efficiencies and future aspirations of skills I wish to learn in this course.
- A Portfolio section with a project video
    The Portfolio section starts with a heading 2 Portfolio, leading to a video file source from the videos folder named reskin.mp4
    The video highlights a previous project of mine using WordPress that showcases a "Treatments" slider, google reviews, header images and footer.
- A footer with copyright text
    My footer is simply the copyright symbol with FreeLivingDesigns company name and the date of copywrite.

## Project Structure
- `index.html`: Main webpage markup and embedded CSS styles.
- `images/`: Stores image assets (`logo.png`, `tom.jpg`).
- `videos/`: Stores video assets (`reskin.mp4`).

## Main Sections in `index.html`

### 1. Document Setup (`<!DOCTYPE html>` and `<head>`)
The file starts with standard HTML5 setup:
- `<!DOCTYPE html>` declares HTML5.
- `<html lang="en">` sets the language to English.
- `<meta charset="UTF-8">` supports standard text encoding.
- `<meta name="viewport" ...>` improves responsiveness on mobile devices.
- `<title>` sets the browser tab title to **FreeLivingDesigns Portfolio Site**.

### 2. Embedded CSS (`<style>`)
The CSS is written directly inside `index.html`.
    I used common HTML5 practises to style my index.html project with best practices.
Key style blocks:
- `body`: Sets base spacing, typography, and centered page alignment.
- `.logo`: Controls logo size and spacing.
- `video`: Makes video responsive with `width: 100%` and `max-width: 600px`.
- `.profile-image`: Styles the profile image with rounded corners and shadow.
- `p`: Centers paragraph text and limits line width for readability.
- `main`: Limits content width to keep layout clean.
- `header`: Controls heading and navigation text alignment.
- `footer` and `footer p`: Center footer content and keep it full-width inside footer.

### 3. Header Section (`<header>`)
Contains:
- Main heading (`<h1>`) with name and role:
  - Tom Black
  - Front-End Web Designer
- Navigation menu (`<nav>`) with anchor links:
  - `#about`
  - `#portfolio`

### 4. About Me Section (`<section id="about">`)
Contains:
- Section title (`<h2>About Me</h2>`)
- Intro paragraph describing background, skills, and interests
- Profile image (`images/tom.jpg`) with descriptive alt text

### 5. Portfolio Section (`<section id="portfolio">`)
Contains:
- Section title (`<h2>Portfolio</h2>`)
- A `<figure>` element with:
  - `<video>` player using `controls`, `loop`, and `muted`
  - `<source>` linked to `videos/reskin.mp4`
  - Fallback text for unsupported browsers
  - `<figcaption>` describing the showcased WordPress project

### 6. Footer Section (`<footer>`)
Contains:
- Copyright line:
  - `© 2026 FreeLivingDesigns. All rights reserved.`

## How to Run
1. Open `index.html` in any web browser.
2. Confirm that the `images/` and `videos/` folders remain in the same project root so assets load correctly.

## Notes
- This is a static front-end project (no JavaScript file and no build step required).
- All styling is currently embedded in `index.html`; I shall be moving styles to a separate `style.css` to improve maintainability as the project grows.
Regards
Tom Black
