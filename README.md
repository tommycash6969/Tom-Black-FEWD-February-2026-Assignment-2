# FreeLivingDesigns Portfolio
Tom Black - FEWD - February 2026 - Assignment 3
## Project Overview
This repository contains my portfolio website for FEWD Assignment 3. The project is built with semantic HTML in `index.html` and a separate external stylesheet in `styles.css`.

The portfolio presents:
- A branded header with navigation
- An About Me section
- A Portfolio section with two WordPress showcase videos
- A footer with copyright information

## Purpose Of The Visual Styling
The styling choices were made to create a modern, confident, and professional portfolio identity with a ctreative style reflecting my personality through my work.

- Colour:
  I used CSS custom properties to keep the colour system consistent across the page. The deep charcoal background (`--main-bg`) adds contrast and seriousness, the hero purple (`--hero-color`) creates a strong visual anchor, and the coral button colour (`--button-color`) gives clear call-to-action emphasis. I decided to use these colours and the "Dust" pallette to keep the colour scheme in a collective and collected style. I wanted to stay within one pallette to ensure all colours worked well together. I used ColorSpace as my reference for the colour pallette theme. I went for a Off Black text colour to give a subtle touch on the eye when reading the paragraph sections.

- Typography:
  I used a clean sans-serif style for clarity and readability. Text spacing and line-height were set to improve scanning and reading, especially in section descriptions and captions. Arial was my main font as I wanted it to be uniform with all browsers without needing downloaded or external fonts that could give errors or faulty outputs later in my project.

  - Layout:
  The page uses a centered, single-column structure with max-width containers, rounded content panels, and responsive media sizing. This keeps the content focused, avoids visual clutter, and scales well on smaller screens. I needed the content to work well on mobile devices and thus used this structure to avoid an outdated look on mobile and tablet devices. I like the rounded corners and believe they soften the entire look of the project, matching that of the buttons.

## Look And Feel + Brand Alignment
The look and feel I aimed for was clean, approachable, and credible, with a balance of creativity and professionalism.

These decisions reflect the FreeLivingDesigns brand by:
- Using a clear visual hierarchy to communicate confidence and structure
- Applying bold accent colours to support a modern design personality
- Keeping navigation and content straightforward so visitors can quickly understand my skills and project examples.

## Changes Reflected In This Version
Compared with the earlier draft, this version now reflects the updated implementation:
- CSS has been moved out of HTML and into `styles.css`
- A reusable colour system has been introduced with CSS variables
- Navigation and interactive controls have clearer hover/focus behavior
- A skip link was added for keyboard and accessibility support
- Responsive spacing and section padding were refined for mobile screens
- Portfolio now includes two video showcase entries, namely Reskin and Sunglideonline
- Two new headings for each portfolio section were added.
- a new backgroundless logo was added and it looks nice on the background colour chosen. 
- I initially started with white text for headings and paragraphs but saw the AA and AAA test failed so went for the dark Grey(off black mentioned earlier).

## CSS Validation Process
I validated the stylesheet using:
-  The W3C CSS Validation Service.
- A standards-based CSS validator workflow (syntax and rules review)
- Manual browser checks for responsive layout and focus visibility
- Constant checking in browser for errors and reviewing AA and AAA verification tools to ensure the projects accessibility for all browsers and users with visual or other imparements.

During validation, I confirmed:
- No CSS syntax errors in `styles.css`
- Consistent variable usage and fallback behavior
- Readable contrast and visible focus states for keyboard users

## Reflection: Challenges, Decisions, And Learning
One challenge was balancing visual style with usability. Strong colours can look good but still need enough contrast and consistent text legibility.

Key decisions I made:
- Use CSS variables to make the palette easier to maintain
- Keep the layout simple and centered so the portfolio content remains the focus
- Add accessibility improvements (skip link and focus states) early rather than as an afterthought

What I learned from styling and validation:
- Separating CSS into its own file improves maintainability and makes iteration faster
- Validation is not just about syntax; it also helps catch user-experience issues
- Small responsive and accessibility adjustments can make a big difference to the overall quality of a portfolio site.

Regards
Tom Black
