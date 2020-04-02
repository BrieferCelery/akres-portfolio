# Scope and Purpose

The purpose of this website is to serve as a professional portfolio for myself. It aims to be an effective marketing tool for my brand and show some of my skills as a developer. The website has four main pages:

- Home Page
- Portfolio of past work
- Biography of myself
- Contact page

To create a modern portfolio site the website must be responsive to multiple screen resolutions on all pages.

## Intended Audience

The intended audience of this website is potential job recruiters, therefore the website must be stylish, easy to use and easy to navigate. In addition it should market myself honestly and professionally.

# Design and Planning

During the design and planning process it was important to consider the constraints of the project. The project is a personal portfolio advertising myself and my brand. This meant that I had to design the site emphasising my strengths in frontend development.

## Tools used

- HTML/HTML5
- Scss
- Nodejs (to compile Scss)
- Git

## Scss

The styling is separated into four files. The `_config.scss` file is used to declare all variables used in the the project as well as set screen resolutions. The mobile.scss file is used to change the elements to fit different screen resolutions. The animations.scss file handled all animations shown on the website. Finally the main.scss is where all styling for each page was done.

## Colour Scheme and font family

`
\$primary-color: #292D33;

\$my-white: #eee;

\$secondary-color: #70C1B3;

\$third-color: #FF1654;

\$font-family: sans-serif;`

## Responsiveness

The different screen resolutions are as follows -

- `mediaSm` small screen: max-width 570px
- `mediaMd` medium screen: max-width 768px
- `mediaLg` large screen: 769px - 1170px
- `mediaXl` extra large screen: min-width 1171px

## Navbar

The navbar was designed with native mobiles apps in mind. A collapsable navbar was the first design choice but

## Design HomePage

The homepage is design using a 2x2 css grid all equal in size. Name and title are place in the the first grid with as a larger heading with a smaller heading underneath. Below that grid are links to other related webpages (github and linkedin). The grid to the right of the links is a cube animation with images of languages and frameworks I am proficient in. This gives the homepage a futuristic feel. The cube rotates slowly and expands when hovered over. It sits in the bottom right grid but expands into the grid above therefore the above grid is left blank.

For smaller screen resoltions only the heading grid and cube grid are kept and all unneccassary space is removed.

## About Page

The about page is a 3x4 grid css grid with varying sizes. The headings follow the same design as done on the homepage with larger and smaller titles. Below the title is another animated circle inspired by the planet saturn. The circle itself is static with multiple rotating rings around it that go through colour transitions as they rotate. Below are styled `divs` with a border on the bottom coloured with my secondary colour.

When displayed on smaller screens the animated circle is removed and all items are stacked in a single column and the styled `divs` expand their width.

## Contact Page

The contact page is simple layout with the same heading scheme used throughout the website. The contact details section has three `spans` inside `divs` with a white border. When hovered over the boxes scale down in size and their background colour transitions to my secondary colour.

Due to the simplistics nature of this page there was not much needed in order to make it accessible for other screen resolutions. The text and boxes are scaled down in order to make it more readable on smaller screens.

## Portfolio page

The portfolio page utilises the grid functionality of css with 3 columns on full resolution. The boxes are styled as a card view with an image header and title below.

As the screen scales down the the column numbers decrease down to 1 column. For medium screens this section becomes a 2x2 grid.
