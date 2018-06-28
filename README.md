# Project 0
[a link](https://mcdomx.github.io/project0/)

## Summary
This site includes a mix of personal and professional resume items.

A bootstrap navigation menu is used to navigate between pages.  In addition to the navigation menu, each page includes a header and a footer which remain static between pages.

Without using Javascript or Python, the menu, header and footer are repeated in each HTML page.  Avoiding this is saved as an exercise when subsequent components are learned later in the class.

#### HTML Pages
- index.html (This is also the "About" page)
- experience.html - A list of professional jobs
- education.html - A list of degrees and institutions as well as special skills
- entrepreneurial.html - Includes a list of part-time businesses I established
- endeavors.html - A list of personal interests, certifications and interests

#### CSS Pages
- css/CSS_project0.css - CSS settings used by the site
- css/bootstrap.min.css - Bootstrap CSS settings

#### Images
- images/email_icon.png - An email icon used to highlight the email link in the footer.
- images/profile_photo.jpg - Profile photo used on About page.


## Requirements
- [X] Four different .html pages where each can be reached from the other.
  - index.html (About page)
  - experience.html
  - education.html
  - entrepreneurial.html
  - endeavors.html
  - A navbar is used on each page to allow navigation to any page from any page

- [X] Includes at least one list (ordered or unordered)
  - All pages, except for the About page, include unordered lists

- [X] Includes at least one table
  - A table is used to display education on the education.html page.

- [X] Includes at least one image.
  - Profile image on the About page (index.html)

- [X] Has at least one stylesheet file.
  - CSS_project0.css includes all applicable CSS settings for the site

- [ ] Stylesheet must use at least five different CSS properties, and at least five different types of CSS selectors.
  - CSS properties used:
    - color
    - padding
    - border
    - vertical-align
    - height
    - margin
    - float
    - NOTE: numerous sub selectors are used for some of these items as well (e.g: margin-bottom)

  - CSS selectors used:
    - a:hover
    - table
    - td
    - th
    - MISSING ONE HERE!!!!!@


- [X] Stylesheet must use the #id selector at least once, and the .class selector at least once.
  - id - id's for #header, #footer and #profile_img are used
  - class - a class for .bosy_text is used

- [X] Stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
  - @media query used to adjust presentation of profile image on index.html

- [X] Use Bootstrap 4 using at least one Bootstrap component
  - multiple bootstrap components in navbar and various div tags.

- [X] Use at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
  - each page uses a two column structure to include the page name in the left column and the page content in the right column.
  - Columns are configured to be mobile-responsive using bootstrap selectors


- [ ] Stylesheets must use at least one SCSS variable.


- [ ] Use one example of SCSS nesting

- [ ] Use SCSS inheritance at least once

- [ ] Include a README.md with project writeup including contents of files and other relevant information
