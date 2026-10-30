# Tech Gadget Store

A responsive static e-commerce website prototype built with **HTML and CSS**. The project was originally developed for Electronic Commerce coursework at the University of Cape Town and has been cleaned for portfolio use.

## Overview

Tech Gadget Store demonstrates a multi-page online retail experience for consumer technology products. It includes product discovery, category browsing, individual product pages, a cart and checkout interface, and responsive layouts for smaller screens.

> **Portfolio note:** This is a front-end prototype. The cart, checkout and contact form demonstrate the user interface flow only; there is no JavaScript application logic, payment processing, database or backend service.

## Features

- responsive layouts for desktop, tablet and mobile screen sizes
- homepage with promotional and featured-product content
- product categories for smartphones, laptops, audio and gaming
- individual product-detail pages
- featured brands and student-focused product collections
- shopping cart and checkout interface
- order-confirmation page
- contact form interface
- embedded product video content
- reusable navigation, cards, buttons, forms and product layouts

## Tech stack

**HTML5 · CSS3 · Responsive Web Design · GitHub Pages**

## Project structure

```text
tech-gadget-store/
├── index.html        # homepage / GitHub Pages entry point
├── html/             # product, category, cart and checkout pages
├── css/
│   └── style.css     # shared site styling and responsive breakpoints
├── images/           # product and banner images
├── videos/           # product videos
└── README.md
```

## Run locally

No build step or package installation is required. Open `index.html` directly in a browser, or serve the repository with any simple static web server.

For example, with Python installed:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Responsive design

The shared stylesheet includes responsive breakpoints for tablet and mobile layouts, adapting navigation, product grids, forms and content sections for narrower screens.

## Portfolio cleanup

The public portfolio version removes coursework declaration documents, adds a GitHub Pages-compatible root entry point, corrects minor copy and page-title inconsistencies, and retains the original website design and implementation.
