# food-delivery-app

Prototype for **Plateful**, a food delivery app built from the *Food Delivery Application — Product Requirements Document* (v1.0, 16 Nov 2026). All restaurants, prices and people are sample data.

## What's here

| Path | Contents |
|---|---|
| `prototype/index.html` | Clickable, responsive prototype in a single self-contained HTML file (no build step, no external dependencies). |

**Figma designs:** [Plateful — Food Delivery App Prototype](https://www.figma.com/design/BfcNdIikBMDjG2q4ro5UOu): 8 mobile screens (390 px) and 4 desktop screens (1440 px), built from shared components and colour tokens.

## Running the prototype

Open `prototype/index.html` in any modern browser. Resize the window to switch layouts:

- **Under 980 px:** mobile/tablet layout with bottom tab bar, floating cart bar and sticky checkout total.
- **980 px and wider:** web layout with top navigation and a side cart panel.

You can also jump straight to a screen with a URL hash: `#home`, `#restaurant/r1`, `#checkout`, `#track`, `#orders`, `#support/FD-47980`, `#account`.

On the tracking screen, the **Prototype controls** advance the order status and simulate a delay, so you can see the push notifications.

## Requirements covered

| Area | PRD requirements |
|---|---|
| Itemized total shown before ordering, kept visible through checkout | FR-01 |
| Arrival times shown as ranges; delay alerts and live tracking | FR-02, FR-03, FR-04 |
| Order history and quick reorder, with unavailable items flagged | FR-05 |
| Search, combinable filters, categories, ratings and reviews | FR-06, FR-07, FR-12, FR-29 |
| Saved delivery instructions and handoff preferences | FR-08, FR-28 |
| In-app issue reporting, phone support and callback | FR-09, FR-10 |
| Recommendations and "find similar" | FR-11, FR-26 |
| Item-level nutrition, with missing data shown as unavailable | FR-13 |
| Simple mode (larger text, no promotions) | FR-14 |
| Item customization with a running price | FR-15 |
| Kid-friendly tags, family bundles, saved order templates | FR-16, FR-17, FR-18 |
| Group ordering without guest accounts, with a per-person cost breakdown | FR-19, FR-20 |
| Scheduled delivery | FR-21 |
| Monthly budget and spend tracking | FR-23 |
| Offers with clear eligibility; subscription disclosure | FR-24, FR-25 |
| Restaurant reliability badges | FR-30 |

Not yet designed: weekly meal planning (FR-22).

## Assumptions to validate

- **Reliability badges:** the "On time 94%" and "Recent delays" figures are invented, because the PRD leaves the method for measuring reliability TBD.
- **Student offer:** the terms (10% off food, maximum $5, $15 minimum food subtotal) are assumed.
- **Fees:** the service fee (6%, minimum $1.50) and the 8% tax rate are placeholders.
