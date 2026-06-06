# Globetrotter — Decisions Log

## Milestone 0: Setup and Planning
- Destination chosen: Japan
- Primary audience: Tourists/ people who want to explore a new country
- One design decision that reflects the destination: Cherry blossoms, and cars maybe
- Wireframe format used (hand-drawn / Figma / other): Hand drawn

## Milestone 1: HTML Structure
_Add entries after building each page._
Gave it a structure, wanted the intro/inital look to be the title with a big beautiful image in the back, i have yet to add it but it follows how i want it to be. Navigation bar has been added as well. 3 little headers with a welcome, about, and quick facts. 

## Milestone 2: CSS Styling
_Add entries after applying styles._
Decided to go with a pink theme to represent the cherry blossoms that japan represents, i also went with having big images in the backround of the headers so that it looks intriguing for people who end up visiting the site. I decided to 
## Milestone 3: Flexbox Layout
_Add entries after implementing Flexbox._
I successfully implemented Flexbox across multiple pages to create a fluid, consistent, and responsive layout. First, I applied Flexbox to the primary navigation bar's un-ordered list, allowing the main navigation links to distribute evenly and stay beautifully centered across the page. On the Home Page, I organized the main container by enabling a flexible wrapping layout so that the Welcome and About blocks sit naturally side-by-side on larger viewports, while the Quick Facts card expands gracefully across the full width of the bottom row.

## Milestone 4: Responsive Design
Added a media query breakpoint at 768px to handle mobile and tablet viewports. On smaller screens, the main navigation links stack vertically so they don't overflow or crowd each other. The hero title and page header text scales down to remain readable without taking over the screen. On the food guide page, the dish layout switches from side-by-side (image left, text right) to a stacked column so the fixed-width image doesn't squeeze the text into an unusable column. Attraction cards and home page sections also collapse to single-column on mobile. The viewport meta tag was already in place across all pages, ensuring the browser scales the layout correctly on phones from the start.

## Stretch Features
- **Animated scroll arrow** — A bouncing chevron arrow was added to the bottom of the hero headers on the Home page and Photo Gallery. It uses a CSS `@keyframes` animation to gently bounce up and down, prompting the user to scroll down. Clicking it jumps directly to the main content section.
- **Google Font integration** — Imported and applied the Japanese-styled Google Font "M PLUS Rounded 1c" (weight 500 and 700) across the entire site for a cohesive, thematic typographic identity that reflects the destination.
- **Traveler-type badge** — Each food guide entry includes a styled pill badge (e.g. "Best for: Families") that categorizes the dish recommendation by traveler type, helping visitors quickly find entries relevant to them.
- **Google Maps link for Tempura** — The Tempura entry's "Learn More" link points directly to a Google Maps search for Tsunahachi in Shinjuku, giving users an actionable way to find the restaurant.