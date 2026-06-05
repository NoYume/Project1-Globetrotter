# Globetrotter — Decisions Log

## Milestone 0: Setup and Planning

- Destination chosen: China
- Primary audience: First-timers, family, and friends
- One design decision that reflects the destination: Using expressive images that showcase both modern and nature
- Wireframe format used (hand-drawn / Figma / other): hand-drawn

## Milestone 1: HTML Structure

_Add entries after building each page._

- Anchored the banner and nav bar onto all web pages to ensure the user can nav between main page and the other pages
- Added sectioned off a certain number of containers per line and isolated them on their own divisions to ensure a grid like pattern for future development
- Added a key title and sub descriptions box for each showcased image across all the images on the website

## Milestone 2: CSS Styling

_Add entries after applying styles._

- Coloring scheme of sapphire blue, black, white, pale gold, and sparingly Jade Green.
- Suggested font of Montserrat but was suggested to use 'Cormorant Garamond', 'Noto Serif SC', Georgia, serif, 'Inter', 'Helvetica Neue', sans-serif
- Made the choice of color of sapphire blue because it supports the idea of modern tech city
- Claude rejected my font of the Montserrat
- The style seems too simple so I plan to add animations or simple transitions or even a video to play

## Milestone 3: Flexbox Layout

_Add entries after implementing Flexbox._

- Added a flex box to the food guide part of the website, the photo section will be able to dynamically change the sizing based on the given screen size
- Claude formatted the photo gallery to be similar format to the food guide page but because there were 6 sections of images, I felt it would be better to have 3 sections of images per line instead of the generated 2 sections
- One challenge was the top attractions page, because there were 3 images, there wasn't a clean and visually appeasing way to format them, I ended up deciding to have 2 images next to each other and a wide shot photo to be a larger section below it to create a "wow" factor to the user

## Milestone 4: Responsive Design

_Add entries after implementing media queries._

- I used a breakpoint for the mobile viewing for 320px since at that point, the size of the section elements would not have enough size to fit two, it instead, a forced formatting to 1 image per line as the user scrolls would be better across all the pages.
- One layout change the mobile viewing needed was the design of the nav bar, on the desktop version, the nav bar is spread across showing all 3 pages as clickable buttons, instead, in the mobile version, the navbar is collapsed to a hamburger button instead and expanded once the user clicks it
- I rejected the Claude suggestion to have the tablet version to showcase 1 image per line, I felt it wasn't needed and would be better to fall back onto the flex box instead to size it accordingly to the available space

## Stretch Features

_Add entries if you implement any stretch features._
