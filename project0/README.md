# Project 0

Web Programming with Python and JavaScript

## Requirements

- Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
  - 5 pages =
     1. Cover page
     2. List of motorbikes
     3. Van Van
     4. Bandit
     5. Info
- Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
  - unordered list = naviagtion links
  - table = list of motorbikes I have owned, with details
  - image(s) = cover page (css background), individual motorbike pages
- Your website must have at least one stylesheet file.
  - styles.css
- Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
  - 1x id = #about
  - 1x class = .card-asd (named with -asd suffix to avoid clash with bootstrap)
  - 5x selectors =
    1. html, body = both html and body
    2. main > .container = container as direct child of main
    3. .asd-card:nth-child(2n) = every other asd-card
    4. a:hover = links being hovered over
    5. a::after = to add content after each link
- Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.
  - card sizes change to show more in a row on larger screens on info page
- You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
  - component = bootstrap cards for motorbike images and captions
  - columns = on individual motorbike pages - to wrap cards
- Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
  - 1x scss variable = card/section background colours on info page
  - 1x scss nesting = card link attributes on info page
  - 1x scss inheritance = special card background and header stars on info page
- In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.
  - See this page
