# Savannah Flame

Savannah Flame is a simple static restaurant website for an African fusion
restaurant in Oslo. It presents the restaurant, its menu, story, gallery, and
contact information in a responsive multi-page frontend.

## Features

- Restaurant homepage with featured dishes and calls to action
- About, menu, gallery, reservations, and contact pages
- Responsive layout for desktop and mobile screens
- Reservation and contact forms handled by [Formspree](https://formspree.io/)
- Deployed on Render for live testing

## Pages

- `index.html` — Home
- `about.html` — Restaurant story
- `menu.html` — Menu and dishes
- `gallery.html` — Restaurant and food gallery
- `reservations.html` — Table reservation form
- `contact.html` — Contact form and location details

## Local preview

Because this is a static site, no build step or package installation is
required. From the project directory, run:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.
