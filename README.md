# CampusEats

**Skip the queue. Browse campus food options and prepare an order from one place.**

CampusEats is a static front-end prototype for a campus food-ordering workflow. It organizes shop/location browsing, menus, cart management, checkout screens, order tokens, and a basic admin interface using HTML, CSS, and JavaScript.

> **Project status:** prototype/demo. The checkout flow simulates payment and does not process real transactions. Client-side storage and demo authentication are not suitable for production accounts, payments, or personal data.

## Features

- Browse campus locations and food shops
- View menus and manage a cart
- Simulated checkout and order-token generation
- Basic order status flow
- Login/authentication screens for demonstrating the UI
- Admin-facing interface for managing sample content
- Responsive front-end pages styled with custom CSS

## Tech stack

- HTML5
- CSS
- Vanilla JavaScript
- Browser local storage for prototype state

## Run locally

No build step is required for the static front end.

```bash
git clone https://github.com/kishorekrrish3/Campus-Eats-Website.git
cd Campus-Eats-Website
```

Open `index.html` in a browser, or serve the repository using a local static web server for more reliable navigation and asset loading.

## Project structure

```text
.
├── index.html       # Main landing page
├── css/             # Stylesheets and design tokens
├── js/              # Cart, menu, shop, order, auth, payment, and admin logic
└── admin/           # Admin-facing pages
```

## Production considerations

- Replace the simulated payment flow with a secure server-side payment integration before accepting money.
- Replace local-storage authentication and order persistence with a backend and secure session handling.
- Enforce authorization and input validation on the server, not only in the browser.
- Do not store passwords, payment details, or sensitive personal data in local storage.
- Add tests for cart totals, order creation, and status transitions.

## Contributing

Bug reports and focused improvements are welcome. Include browser details and clear reproduction steps.
