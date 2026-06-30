# TrainingAssignment1 - Geeks Clone

This project is a static front-end clone of a learning platform inspired by Geeks. It includes a home page with course carousels and a course details page with tabs, accordions, and responsive navigation.

## Project Structure

- `geeksClone/index.html` - landing page with hero section, featured benefits, and course cards.
- `geeksClone/course.html` - course details page for a JavaScript course.
- `geeksClone/css/` - custom styling for the layout, navbar, home page, and course page.
- `geeksClone/Images/` - logos, avatars, and course thumbnails used by the pages.

## Pages

### Home page

The home page includes:

- A sticky Bootstrap navbar with multi-level dropdown menus.
- A hero section with call-to-action buttons.
- A quick benefits strip highlighting online courses, expert instruction, and lifetime access.
- Three course sections: Recommended to you, Most Popular, and Trending.
- A Slick carousel for course cards with responsive breakpoints.
- A footer with privacy, terms, feedback, and support links.

### Course page

The course page includes:

- A hero banner for "Getting Started with JavaScript".
- Course metadata such as enrollment count, rating, and difficulty.
- Tabbed content for Contents, Description, Reviews, Transcript, and FAQ.
- Accordion-based lesson modules in the Contents tab.
- A floating Buy Now button in the footer area.

## Tech Stack

- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons
- Font Awesome
- jQuery
- Slick Carousel

## Features

- Responsive layout for desktop and mobile screens.
- Hover-based dropdown menus on larger screens.
- Mobile-friendly submenu handling for nested navigation.
- Course sliders with custom previous/next arrows.
- Reusable utility classes and color variables in shared CSS files.

## How to Run

This is a static site, so no build step is required.

1. Open the `TrainingAssignment1/geeksClone/index.html` file in your browser.
2. Or open the `TrainingAssignment1/geeksClone/` folder in VS Code and use a live server extension if you want automatic reload.

## Notes

- The pages load several assets from CDNs, including Bootstrap, icons, Google Fonts, jQuery, and Slick Carousel.
- The `course.html` page links to `index.html` from one of the course cards.
