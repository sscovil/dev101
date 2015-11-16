# Dev 101 / Challenges / Responsive Markup

Before you start writing code, it is important to have a solid foundation. Learn how to write good, clean markup
and style it with CSS. If you are not familiar with HTML & CSS, start with the Responsive Markup challenge.

### Courses

1. Code School: [Front-end Foundations](https://www.codeschool.com/courses/front-end-foundations)
1. Code School: [Front-end Formations](https://www.codeschool.com/courses/front-end-formations)
1. Code School: [CSS Cross-Country](https://www.codeschool.com/courses/css-cross-country)
1. Code School: [Journey Into Mobile](https://www.codeschool.com/courses/journey-into-mobile)

### Challenge

Go to [Plunker](http://plnkr.co) and create a mobile-first layout for a web application.

Requirements:

1. The app should have a header, main content area, two sidebars, and footer
1. The header should contain:
    1. a logo image (http://placehold.it/240x180) left-justified
    1. a horizontal navigation menu (right justified) with three links: Home, About, Contact
1. The main content area should contain:
    1. a headline
    1. a subhead with author name and publication date
    1. an image placeholder (http://placehold.it/460x280)
    1. an article with at least three paragraphs of placeholder text (http://www.lipsum.com/feed/html)
    1. a few buttons for sharing the article on social media (e.g. Twitter, Facebook, LinkedIn)
1. Sidebar #1 should contain an unordered list of at least five links to other articles (just use href="#" so the links
don't navigate anywhere)
1. Sidebar #2 should contain at least two advertisements in the form of image links (http://placehold.it/200x200)
1. The footer should contain a centered copyright notice (ex: "&copy; 2015 Shaun Scovil")
1. On small screens (up to 600px wide):
    1. the menu should be replaced with an icon (ex: http://fortawesome.github.io/Font-Awesome/icon/bars/)
    1. sidebar #1 should appear below the main content area
    1. sidebar #2 should appear below sidebar #1
1. On medium screens (601px - 960px wide):
    1. sidebar #1 should appear to the left of the main content area
    1. sidebar #2 should appear below the main content area and sidebar #1
1. On large screens (greater than 960px wide):
    1. sidebar #1 should appear to the left of the main content area
    1. sidebar #2 should appear to the right of the main content area

Make sure there is a gutter between the sidebars and main content area (8px margins should suffice). Be sure images
do not extend beyond the width of their containers, particularly on small screens (use max-width).
