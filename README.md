# Ultra – Online Shopping Website

A multi-page e-commerce front-end built by a student team with **HTML5, CSS3 and  JavaScript**.

## Features
- Product listing pages with hover cards and category search routing
- Shopping cart persisted in `localStorage` (add / change quantity / remove / total / live badge)
- Checkout, login and register forms with client-side validation and toast feedback
- Responsive layout, shared design tokens (`style.css`), accessible focus states, reduced-motion support

## Structure
| File | Purpose |
|---|---|
| `index.html`, `about.html`, `contact.html` | Landing & info pages |
| `product_section.html`, `Phones & Tablets.html` | Catalogue pages |
| `cart.html`, `pay.html`, `my_orders.html` | Purchase flow |
| `login.html`, `registerform.html`, `user_final.html` | Account pages |
| `style.css` | Shared design system (colors, nav, cards, forms) |
| `app.js` | Cart, validation, search, toast, shared footer |

## Run locally
Open `index.html`, or: `python -m http.server 8000` then visit http://localhost:8000
