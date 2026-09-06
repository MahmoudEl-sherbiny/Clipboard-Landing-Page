# Clipboard landing page

This project is a static implementation of the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9).
## Table of contents

- [Overview](#overview)
  - [Implemented features](#implemented-features)
- [Screenshot](#screenshot)
- [Built with](#built-with)
- [Interactions](#interactions)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Implemented features

The page currently includes:

- Clipboard product introduction and feature sections
- Responsive desktop, tablet, and mobile layouts
- iOS and Mac download call-to-action buttons
- Snippet feature details, workflow tools, supported companies, and footer navigation
- Clipboard logo, product imagery, company logos, and social media icons from the provided assets

### Screenshot

![Preview of the Clipboard landing page](./preview.jpg)

## Built with

- Semantic HTML5 markup
- CSS with Flexbox and CSS Grid layouts
- Responsive CSS media queries for tablet and mobile breakpoints
- Vanilla JavaScript
- [Bai Jamjuree](https://fonts.google.com/specimen/Bai+Jamjuree) loaded from Google Fonts
- Provided PNG and SVG image assets

## Interactions

- Buttons have hover and active states implemented in CSS.
- Page sections use the `IntersectionObserver` API to reveal themselves as they enter the viewport.
- The company logo track scrolls continuously and pauses when hovered.
- Footer and social links are present as layout elements, but currently use placeholder `#` destinations.
- The download buttons are visual call-to-action buttons and do not currently initiate downloads.

## Author

- Coded by Mahmoud Elsherbiny

## Acknowledgments

Design and starter assets provided by [Frontend Mentor](https://www.frontendmentor.io/).
