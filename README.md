# FoodieHub

## Project Description
FoodieHub is a modern, responsive food delivery website concept. It showcases a full customer-facing frontend — browsing food categories, viewing popular dishes, registering/logging in, and completing a demo checkout — built entirely with static HTML5 and CSS3.

This is a **frontend-only project**. There is no backend, database, or JavaScript — forms are for visual demonstration only and do not submit or validate data.

## Features
- Fully responsive layout (mobile, tablet, desktop)
- Sticky, accessible navigation bar with a mobile menu (CSS-only, no JavaScript)
- Hero section with call-to-action buttons
- Food category grid (Pizza, Burger, Noodles, Curry, Dessert, Drinks)
- Popular food cards with images, pricing and hover effects
- "Why Choose FoodieHub" feature highlights
- About page with mission, vision and feature highlights
- Services page with a six-service grid and a 3-step process strip
- Login and Register pages with styled forms
- Payment page with an order summary and UPI / Card / Cash-on-Delivery method selector (CSS-only tabs)
- Legal page with Terms & Conditions, Privacy Policy, Refund Policy, Delivery Policy and User Responsibilities
- Consistent design system (colour palette, typography, buttons, cards) across every page
- Subtle CSS transitions and hover animations throughout
- Semantic HTML5, labelled form fields, alt text on all images, visible focus states, and a skip-to-content link on every page

## Technologies Used
- HTML5 (semantic markup)
- CSS3 (Flexbox, Grid, custom properties, transitions — no frameworks)
- Google Fonts (Fraunces + Work Sans, loaded via `@import` in the CSS files)
- No JavaScript, no build tools, no backend

## Folder Structure
```
foodiehub/
├── index.html
├── about.html
├── services.html
├── login.html
├── register.html
├── payment.html
├── legal.html
│
├── css/
│   ├── index.css
│   ├── about.css
│   ├── services.css
│   ├── login.css
│   ├── register.css
│   ├── payment.css
│   └── legal.css
│
├── images/
│   ├── logo.png
│   ├── food-hero.jpg
│   ├── pizza.jpg
│   ├── burger.jpg
│   ├── noodles.jpg
│   ├── curry.jpg
│   ├── dessert.jpg
│   └── drinks.jpg
│
└── README.md
```

> Note: the images included are original stylised placeholder graphics (not real photography), generated to keep the project self-contained. Swap the files in `images/` with real photos of the same names to give the site a photographic look — no HTML/CSS changes are needed.

## Pages Description
| Page | File | Description |
|---|---|---|
| Home | `index.html` | Hero, food categories, popular dishes, "Why Choose FoodieHub", and a closing call-to-action. |
| About | `about.html` | Company story, mission, vision, "Why FoodieHub" list, and delivery feature highlights. |
| Services | `services.html` | Six core services as cards, plus a 3-step "how it works" process. |
| Login | `login.html` | Email/password login form with remember-me and links to Register and Home. |
| Register | `register.html` | Sign-up form (name, email, phone, password, confirm password) with a link to Login. |
| Payment | `payment.html` | Order summary and a demo checkout with UPI, Card, and Cash on Delivery options. |
| Legal | `legal.html` | Terms & Conditions, Privacy Policy, Refund Policy, Delivery Policy, and User Responsibilities. |

## How to Run
1. Download or clone the `foodiehub` folder.
2. Open `index.html` directly in any modern web browser (double-click it, or right-click → Open With → your browser).
3. Navigate the site using the navbar — no server or installation is required.

## Future Improvements
- Connect the login, register and payment forms to a real backend and database.
- Add real product photography in place of the placeholder images.
- Add a working cart system and dynamic order totals (would require JavaScript).
- Add real-time order tracking and restaurant search/filtering.
- Add user reviews and ratings for dishes and restaurants.
