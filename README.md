# HelpPal — UNILAG Errand Demo

A responsive React + TypeScript + Vite prototype for a campus errand-running service. All people, orders, prices, availability, and tracking are fictional. No backend, external API, GPS, or real payment integration is used.

## Run locally

Requirements: Node.js 20+ and npm.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. To build a production bundle:

```bash
npm run build
npm run preview
```

## Demo journey

1. Open the landing page and choose **Get started**.
2. Select a customer or agent account. No password is needed.
3. As a customer, create an errand through the category, store, item list, delivery, and review steps.
4. Choose an available demo agent, then open the order details to advance the simulated status timeline.
5. Switch to an agent account to accept requests and update assigned errands. Changes are persisted in localStorage in the same browser.
6. Use **Reset demo data** in the sidebar or profile settings to restore the sample dataset.

## Included

- 8 fictional agents, 5 customer profiles, and 12 sample errands.
- Customer and agent dashboards, order history, status filters, notifications, and detail pages.
- LocalStorage persistence with malformed-data fallback.
- Editable shopping items, estimated distance, item subtotal, service fee and transport estimate.
- Responsive layout, keyboard-visible focus styles, and confirmation dialogs.

## Demo pricing

- Up to 3 miles: ₦50 service fee.
- Above 3 and up to 5 miles: ₦100.
- Above 5 and up to 10 miles: ₦150 configurable placeholder.
- Above 10 miles: ₦200 service fee plus an estimated transport calculation.

These are demonstration placeholders, not commercial quotes. All distances and arrival times are estimates and are not based on live GPS.
