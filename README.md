# web5121_POE
# Sol de Janeiro — Static Landing Page

Simple static landing page showcasing Sol de Janeiro product lines. Built with Bootstrap and custom CSS.

## Quick start
1. Open the project folder in your editor (VS Code).
2. Open [index.html](index.html) in a browser or use the Live Server extension.
   - File: /Users/wanga/Documents/code/Wanga_tshidada_web_dev_poe/index.html
3. Styles are in [style.css](style.css).
   - File: /Users/wanga/Documents/code/Wanga_tshidada_web_dev_poe/style.css

## Features
- Sectioned single-page layout (landing, fragrances, skincare, story, testimonials, how-to, store, footer).
- Responsive layout using Bootstrap 5 CDN.
- Accessible anchor links that navigate to page sections (IDs like #fragrances, #skincare, #story, #testimonials, #how-to, #location).

## File structure
- index.html — main HTML page
- style.css — custom styles
- images/ — images used on the page
- icons/ — svg icons

## How to edit navigation links
- Ensure each nav link's href matches a section ID in [index.html](index.html). Example:
  - Navbar link: <a href="#fragrances">Fragrances</a>
  - Target section: <section id="fragrances">...</section>
- If adding/removing sections, update both the navbar and the section id.

## Local development tips (macOS)
- Open project directory in Terminal:
  cd "/Users/wanga/Documents/code/Wanga_tshidada_web_dev_poe"
- Start a quick server (if needed):
  python3 -m http.server 8000
  Then visit http://localhost:8000/index.html

## Notes
- Bootstrap is loaded via CDN in index.html — no package install required.
- Update image paths in the `images/` folder and ensure filenames match those referenced in index.html.

