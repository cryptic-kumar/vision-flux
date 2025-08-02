# VISIONFLUX – Immersive Web Experience

VISIONFLUX is a futuristic and interactive website created for the PixxelHack Webathon 1.0. It brings together advanced front-end animations, responsive design, and creative UI elements to deliver a rich, engaging user experience. Built entirely with HTML, CSS, and JavaScript, every effect has been handcrafted without the use of frameworks.

## Overview

This project demonstrates a creative approach to building immersive web interfaces using visual storytelling, animations, and device adaptability. It focuses on delivering smooth interactions, seamless navigation, and visual appeal across multiple sections.

## Key Features

- Loader animation that introduces the site
- Scroll-based hero text resizing
- Marquee animation showcasing key topics
- Floating blob animation that follows the cursor
- Ripple click effect integrated as a mystery element
- Auto-typing animation for dynamic headlines
- Responsive image grid with 3D tilt hover effects
- Team page with launch teaser and animated content
- Contact form with glowing fields and transition animations
- Fully responsive and device-compatible layout

## Elements Used (from given list)

- Marquee scrolling text
- Scroll-based text resizing
- Auto-typing animation
- 3D card tilt effect
- Floating blob animation
- Responsive grid layout
- Loader transition

## Mystery Element Implementation

As part of the competition requirement to include a unique element beyond the given list, a **Ripple Click Effect** was implemented throughout the website. This effect creates a smooth circular wave at the location of each click, giving the interface a dynamic and tactile response.

### How it was used:

- A `<span>` element styled as a translucent circle is positioned at the user's click location using JavaScript.
- Each click removes the previous animation and retriggers it by forcing a reflow.
- The effect is applied globally across all pages, enhancing every interaction, including button presses and clicks anywhere on the screen.
- This element was implemented using only custom CSS and JavaScript, making it lightweight and fully reusable.

This ripple animation acts as a **visual feedback system**, making user interactions feel more intuitive and engaging — fulfilling the mystery element criteria with originality.

## Project Structure

The project includes six fully developed HTML pages with all styles and scripts included inline. No external folders are required for functionality.

- index.html
- about.html
- experiments.html
- team.html
- contact.html
- 404.html
- README.md

## Tech Stack

- HTML5 for semantic structure
- CSS3 for animations and responsive styling
- JavaScript for interactivity and DOM effects
- Google Fonts for styling

## Responsiveness

All pages are designed to work smoothly on mobile phones, tablets, and large screens. Layouts and font sizes adjust automatically based on the screen size.

## Learning Outcome

Through this project, several interactive web techniques were implemented without external libraries. It offered a deeper understanding of DOM manipulation, animation principles, responsive design, and modern UI effects.

## Acknowledgements

This website was developed as a submission for the PixxelHack Webathon 1.0. All design, development, and animations were created by Aditya Kumar Sah.

## License

This project was submitted for a competition and is not intended for public redistribution or commercial use without prior permission.
