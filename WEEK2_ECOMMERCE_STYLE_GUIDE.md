# Week 2 Mini Project — Shoply E-commerce Mobile App

**Project brief:** Design a complete e-commerce mobile app with 10 screens and a style guide covering typography, colour, and spacing.

**Deliverables in this repository**
- `WEEK2_ECOMMERCE_STYLE_GUIDE.md` — UX rationale, design system, screen specs, and accessibility checks.
- `shoply-ecommerce-prototype.html` — responsive clickable prototype with 10 screen views.

> **Scope note:** This is a high-fidelity visual direction and interactive HTML prototype for the assignment. It is not connected to a payment provider, inventory system, or real user account. Product prices and content are sample data.

## Product concept
**Shoply** is a friendly, modern mobile shopping experience for everyday lifestyle products. It prioritizes product discovery, transparent pricing, clear shipping information, and a short checkout flow.

### Target users and design goals
- People who want to find products quickly on mobile.
- Returning shoppers who want to revisit saved items and orders.
- Users who need predictable checkout and clear costs before placing an order.

**Core goals:** make search visible, make product information scannable, reduce checkout uncertainty, support wishlisting, and keep navigation consistent.

## The 10 screens

1. **Home:** search field, promotional hero, categories, curated products, bottom navigation.
2. **Categories:** browsable category grid and category shortcuts.
3. **Product detail:** product image, price, rating, options, delivery note, add-to-cart and wishlist.
4. **Cart:** editable quantities, remove item, subtotal and checkout CTA.
5. **Checkout:** contact and delivery form, delivery option, order summary, place-order demo action.
6. **Profile:** account summary and shortcuts to orders, wishlist and settings.
7. **Orders:** order history cards and status labels.
8. **Search:** query input, filter chips, matching products and empty state.
9. **Wishlist:** saved products, remove from wishlist, add to cart.
10. **Settings:** notification preferences, privacy/help shortcuts and display preferences.

## Visual design system

### Colour tokens
| Token | Hex | Use |
|---|---|---|
| Ink | #20231F | Primary text |
| Forest | #245C45 | Primary action, active navigation |
| Mint | #E5F3EA | Soft surfaces and highlights |
| Cream | #FAF8F3 | Main background |
| White | #FFFFFF | Cards and input surfaces |
| Muted | #70766F | Secondary text |
| Border | #E4E7E1 | Dividers and field outlines |
| Coral | #D9674F | Sale/attention accent; use sparingly |

Colour should support hierarchy rather than carry meaning alone. Statuses also have text labels.

### Typography scale
Use a system sans-serif stack for a robust, readable interface.
- **Display / hero:** 30 px, 1.15 line-height, 700 weight.
- **Page heading:** 24 px, 1.25 line-height, 700 weight.
- **Section heading:** 18 px, 1.3 line-height, 650–700 weight.
- **Body:** 15–16 px, 1.5 line-height, 400 weight.
- **Supporting text:** 13–14 px, 1.4 line-height.
- **Label / metadata:** 12 px, 1.35 line-height, 600 weight.
- Use sentence case, avoid long all-caps labels, and never use colour alone to distinguish text hierarchy.

### Spacing and layout
Use a 4 px base spacing scale: 4, 8, 12, 16, 20, 24, 32, 40, 48 px.
- Screen side padding: 20 px on mobile.
- Card padding: 16 px.
- Space between sections: 24–32 px.
- Button minimum height: 48 px.
- Tap targets: aim for at least 44 × 44 px.
- Card radius: 16 px; pill controls: fully rounded.
- Keep a consistent 8-point rhythm where possible and align content to a shared grid.

### Components
- Primary button: forest fill, white text, minimum 48 px height.
- Secondary button: white/cream surface with border.
- Product card: image area, concise title, price, optional rating and wishlist control.
- Search field: visible label or accessible name, leading search icon, clear affordance.
- Form fields: persistent labels, clear focus state, validation text adjacent to field.
- Navigation: consistent labels and selected state across screens.
- Feedback: visible cart count, success confirmation, and clear empty states.

## Interaction and flow
- Home → categories or search → product detail → add to cart → cart → checkout.
- Product detail can toggle wishlist status.
- Cart quantities update subtotal; removing the final item displays an empty state.
- Search filters the sample product list as the query changes.
- Wishlist supports removing saved items and adding items to cart.
- Profile links to orders, wishlist, and settings.
- Checkout uses a demo confirmation only. No real payment or order is submitted.

## Accessibility / WCAG review checklist
- Aim for WCAG 2.2 AA contrast: 4.5:1 for normal text and 3:1 for large text and meaningful UI boundaries.
- Use semantic headings, labelled controls, descriptive button text, and visible keyboard focus.
- Do not rely on colour alone for sale, selected, or order status.
- Provide useful alt text for meaningful product images; decorative images should have empty alt text.
- Ensure interactive controls work with keyboard and have comfortable touch targets.
- Associate validation messages with fields and announce confirmation messages accessibly.
- Respect zoom and narrow viewport reflow; avoid horizontal scrolling at mobile widths.
- Test colour contrast with a contrast checker before final Figma handoff.

## Handoff and validation
1. Review all ten screens at a mobile viewport.
2. Test search, category navigation, cart quantity changes, wishlist actions, and checkout demo.
3. Replace sample products/content with researched content if required.
4. Recreate or refine these frames in Figma if the course requires a native Figma file.
5. Run a contrast checker and usability test with representative users before final delivery.

## Running the prototype
Open `shoply-ecommerce-prototype.html` in a modern browser. It has no external dependencies and uses sample data only.
