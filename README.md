# Spice Slice

our live site is here
[View the live site](https://spice-slice.netlify.app/.)

A simple, responsive restaurant landing page for Spice Slice, a vegetarian restaurant concept in Chennai. The page highlights the menu, restaurant locations, and an external online-order link.

## Features

- Hero section with restaurant branding and an online-order button
- Menu grouped into starters, main course, and chats, with prices in Indian rupees
- Address details for Anna Nagar, Velachery, and Tambaram
- Responsive menu layout using CSS Grid and Flexbox
- Background image and SVG favicon from the local media folder

## Project Files

```text
.
├── index.html
├── style.css
└── media/
    ├── bg.jpg
    └── logo.svg
```

## Run Locally

No build step or package installation is required. Open `index.html` in a browser, or serve the project directory with any static file server. For example, with Python installed:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Notes

- The **Order Online** button opens Swiggy in a new tab; it is not connected to a restaurant-specific ordering page yet.
- Font Awesome icons are loaded from a CDN, so an internet connection is needed for those icons to appear.
- Menu items, prices, contact details, and location information are currently written directly in `index.html`.