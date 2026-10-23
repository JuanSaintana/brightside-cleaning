# Brightside Home Cleaning

Online booking store for a house cleaning business, in one HTML file (open `index.html` in a browser).

## Features
- Instant quote: Standard, Deep, and Move in/out cleans priced by bedrooms, bathrooms, and home size
- Add-ons (oven, fridge, windows, cabinets, laundry, pet hair) and recurring discounts (weekly 20%, every 2 weeks 15%, monthly 10%)
- Room-by-room checklist per service
- Gift cards, cart (saved in localStorage), promo code `FIRSTCLEAN` (10% off cleans)
- Checkout: details → day and arrival window → review → confirmation
- Light and dark themes

## To make it real
- Replace the placeholder name, prices, phone, and email
- Payments: connect something like Stripe
- Bookings: send orders to email, a calendar, or a database (currently demo-only)
- Remove the `<meta name="robots" content="noindex">` tag in `index.html` so search engines can list the site

## Where to edit
Prices, services, add-ons, and promo codes are the `SERVICES`, `ADDONS`, `FREQ`, and `PROMOS` constants at the top of the `<script>`.
