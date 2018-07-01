# Project 0
[Link to project0 page](https://mcdomx.github.io/project0/)

## Summary
This site includes a mix of personal and professional resume items.

A bootstrap navigation menu is used to navigate between pages.  In addition to the navigation menu, each page includes a header and a footer which remain static between pages.

Without the knowledge of additional tools, the menu, header and footer are repeated in each HTML page.  I expect we will learn how to avoid this later in the class.

A separate css file was used for SCSS components in order to highlight satisfied requirements.  All css could have been combined into one file but was left separate for assignment grading readability.

The viewport meta tag on each page was adjusted to allow reasonable display on my retina mobile device.  I did not take measures to ensure that the site looked reasonable on all mobile devices since this was outside the scope of the assignment.

#### Frameworks
- In addition to HTML and CSS, the following frameworks were installed and used:
  - SAAS - to use SCSS (SCSS_project0.scss is the source and SCSS_proect0.css is the target.)
  - Bootstrap - referenced in header via web link to bootstrap css file.

#### HTML Pages
- Each page includes a tailored bootstrap grid that changes the nav menu and contents as the viewport changes width.

  - index.html (This is also the "About" page)
  - experience.html - A list of professional jobs
  - education.html - A list of degrees and institutions as well as special skills
  - entrepreneurial.html - Includes a list of part-time businesses I established
  - endeavors.html - A list of personal interests, certifications and interests

#### CSS/SCSS Pages
- css/bootstrap.min.css - Bootstrap CSS settings
- css/CSS_project0.css - CSS settings used by the site
- css/SCSS_project0.css/scss - Saas settings used by the site

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
  - CSS_project0.css includes non-SCSS applicable CSS settings for the site
  - SCSS_project0.css(SCSS) includes the SCSS configurations

- [X] Stylesheet must use at least five different CSS properties, and at least five different types of CSS selectors.
  - CSS properties used:
    - color
    - padding
    - border
    - vertical-align
    - height
    - margin
    - float
    - NOTE: numerous sub-selectors are used for some of these items as well (e.g: margin-bottom)

  - CSS selectors used:
    - a:hover
    - table (included in the SCSS css page)
    - td (included in the SCSS css page)
    - th (included in the SCSS css page)
    - p

- [X] Stylesheet must use the #id selector at least once, and the .class selector at least once.
  - id - id's for #profile_img and #navigation are used
  - class - classes for .body_text, .nav-link and .table-data-cells are used

- [X] Stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
  - @media query used to adjust presentation of profile image on index.html

- [X] Use Bootstrap 4 using at least one Bootstrap component
  - multiple bootstrap components in navbar and various div tags.

- [X] Use at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
  - each page uses a two column structure to include the page name in the left column and the page content in the right column.
  - Columns are configured to be mobile-responsive using bootstrap selectors

- [X] Stylesheets must use at least one SCSS variable.
  - Used two color variables for the background and text for the header, footer and nav bar.

- [X] Use one example of SCSS nesting
  - Table headers \<th\> and cells <td> use SCSS nesting inside of the \<table\> tag.

- [X] Use SCSS inheritance at least once
  - Used shared settings for the header and footer in an inheritable section and included them in the header and footer tags.
  - Also used inheritance for table cell formatting.

- [X] Include a README.md with project writeup including contents of files and other relevant information
