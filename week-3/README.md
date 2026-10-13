# Week 3 — Orbit SaaS Dashboard Design System

A responsive SaaS dashboard prototype and component system built with semantic HTML, CSS, and vanilla JavaScript. No build step or external dependencies required.

## Run it
Open `index.html` in any modern browser. On GitHub, open **week-3/index.html** and use the preview/deploy option (GitHub Pages can be enabled from Settings → Pages, deploying from the main branch and root if you move the file to root, or from a Pages-compatible publishing setup).

## Screens (5)
1. **Overview** — KPI cards, animated revenue line chart, customer-plan donut, recent customer table.
2. **Analytics** — recurring revenue, churn, lifetime value, traffic source bars, and conversion funnel; export report to CSV.
3. **Customers** — searchable, filterable customer table; add customer with validation and immediate UI update.
4. **Projects** — responsive project cards with progress indicators; create project via modal.
5. **Settings** — profile/workspace forms and interactive notification toggles.

## Design system
- **Color tokens:** brand indigo `#5B5CE2`, ink `#172033`, background `#F5F7FB`, surface white, muted slate, semantic green/orange/red.
- **Typography:** system sans-serif stack; clear type scale, bold page headings, compact labels.
- **Components:** primary/secondary/ghost/danger buttons, inputs, selects, KPI cards, status pills, tables, progress bars, avatars, modals, toast alerts, navigation, toggles, charts.
- **Responsive behavior:** desktop sidebar, mobile slide-out navigation, responsive KPI/project grids, horizontal table scrolling, stacked settings form.
- **Interactions:** navigation transitions, modal open/close (Escape/backdrop/cancel), live customer search and filters, create customer/project, notification toggles, analytics CSV export, period selector feedback, toast confirmations.

## Heuristic evaluation (prototype review)
1. **Visibility of system status:** toast confirmations and status pills provide feedback after saving, adding, exporting, and toggling.
2. **Match with real-world language:** labels such as Customers, Projects, Revenue, and Settings match familiar SaaS conventions.
3. **User control and freedom:** modals can be cancelled with a button, backdrop click, or Escape.
4. **Consistency and standards:** reusable tokens, spacing, button variants, cards, tables, and status colors are shared across screens.
5. **Error prevention:** required form fields, email input type, and settings name validation reduce invalid submissions.
6. **Recognition rather than recall:** persistent sidebar navigation, breadcrumbs, labels, and visible filters help users orient themselves.
7. **Flexibility and efficiency:** customer search can be combined with status and plan filters; analytics report exports as CSV.
8. **Aesthetic and minimalist design:** cards prioritize key metrics and avoid unnecessary visual noise.
9. **Help users recover from errors:** empty search results show a helpful message; validation focuses the invalid field.
10. **Accessibility:** semantic buttons, labels, dialog roles, visible focus styles, status live region, and ARIA labels are included.

## Suggested next improvements
- Persist user-created customers/projects and settings with a backend.
- Add keyboard focus trapping inside dialogs and more comprehensive screen-reader chart descriptions.
- Connect charts to live data and add automated browser/accessibility tests.

## Files
- `index.html` — complete working prototype and embedded component styles/scripts.
- `README.md` — overview, design tokens, screen map, interactions, and heuristic review.
