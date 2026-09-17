# RESTAURANT

A static, multi-page restaurant website built with **HTML, CSS and Bootstrap 4**. Showcases the restaurant's home page, menu, about, contact, and table reservation pages.

## Tech Stack

- HTML5 / CSS3
- Bootstrap 4 (bundled locally under `dist/`)
- Font Awesome (icons)
- bootstrap-social (social media buttons)
- jQuery, Popper.js

No build step or backend — plain static assets served as-is.

## Pages

| Page | File |
|---|---|
| Home | `index.html` |
| About Us | `aboutus.html` |
| Menu | `menu.html` |
| Contact Us | `contactus.html` |
| Reservations | `reserve.html` |

## Project Structure

```
├── index.html / aboutus.html / menu.html / contactus.html / reserve.html
├── styles.css              # Custom site styles
├── *.png / *.jpg / *.jpeg  # Site images (logo, dishes, banners)
├── dist/                   # Bootstrap CSS & JS
├── font-awesome/           # Font Awesome library
├── bootstrap-social/       # Social icon button styles
└── js/dist/                # Individual Bootstrap JS components
```

## Running Locally

No dependencies to install — just open `index.html` in a browser, or serve the folder locally:

```bash
# Python
python3 -m http.server 8000

# Node
npx serve .
```

Then visit `http://localhost:8000`.

## Disclaimer

Sample/learning project for practicing front-end web development with Bootstrap.
