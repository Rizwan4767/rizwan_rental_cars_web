# Stackly Drive | Car Rental Homepage Demo

A responsive single-page car rental landing page built with HTML, CSS and vanilla JavaScript, using GSAP hero animations and AOS scroll reveals.

## Run locally

 Open the `stackly-homepage` folder in VS Code.
 Run `index.html` with Live Server.

## Homepage features
- Premium midnight-navy, ivory and lime palette.
- Hero section, responsive navigation and booking/search panel.
- Sample vehicle cards for economy, SUV and luxury categories.
- Benefits, booking steps, quote section and final CTA.
- GSAP entrance animations, AOS reveals, responsive layout and reduced-motion support.
- Booking form validates date order and filters the demo fleet by category. It does not connect to a real inventory, payment or booking backend.
- All non-homepage HTML pages redirect to the custom `404.html` page, as requested.

## Before production
- Replace sample daily rates, vehicle descriptions, quote and image choices with approved business content.
- Configure real fleet availability, rental terms, deposit/insurance rules, booking confirmation and payment through a backend.
- Configure hosting to serve `404.html` for unknown URLs as well as the included redirect stub pages.
- Fonts, photos, GSAP and AOS are loaded from external CDNs and need an internet connection.
