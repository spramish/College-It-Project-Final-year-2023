# Explore Japan — College IT Project (2023)

A static, multi-page tourism website about Japan, built with pure **HTML5** and **CSS3** — no JavaScript, no frameworks, and no build tools. Created as a final-year college IT project in 2023.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Full-screen background video hero, intro heading, and a "DISCOVER More About Japan" link |
| Login | `1st login page.html` | Login form over a background video |
| About Us | `about us .html` | Japan's nine regions and its major cities, shown as animated image cards |
| Gallery | `gallery.html` | A grid of "Things to do in Japan" cards with photos |
| Packages | `packages.html` | Luxury hotels, famous Japanese food, and cultural traditions |
| Contact Us | `contact us.html` | Fill-up form (name, email, date, time, message) with a video background |

Every page shares a common top navigation bar (with a search box) and a footer with social-media links and a copyright line.

## Tech Stack

- **HTML5** — semantic structure, tables, forms
- **CSS3** — Flexbox layout, linear gradients, fixed background video, hover transitions
- Google Fonts (Poppins) via `@import`

## Project Structure

```
.
├── index.html
├── 1st login page.html
├── about us .html
├── gallery.html
├── packages.html
├── contact us.html
├── index.css
├── 1st login page.css
├── about us.css
├── gallery.css
├── packages.css
├── contact us.css
├── wireframe.pdf
└── image/
    ├── logo2.png
    ├── vdieo.mp4      (home background video)
    ├── login.mp4      (login / contact background video)
    └── ...            (photos used across the pages)
```

## Getting Started

No installation or server is required:

1. Open the project folder.
2. Double-click `index.html` (or open it in any modern browser).
3. Use the top navigation bar to move between the pages.

> Tip: for the background videos to load reliably, open the site through a local folder — all paths are relative and resolve to the `image/` directory.

## Author

**Pramish Sharma**

## Notes

This project was built for academic purposes as a 2023 college IT submission.
