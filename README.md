# Katalian MedSource

A demo pharmacy-ordering portal used as a test target for Katalon demos. It covers product search, Quick Add & Scan, multi-cart management with Non-C2 and C2 carts, CSOS purchase confirmation, order history, backorders and messages.

All data is fictional and lives in the browser (localStorage). There is no backend or database.

## Demo logins

| Username | Password | Accounts |
|---|---|---|
| `buyer` | `Demo123!` | Two pharmacies (account switcher enabled) |
| `solo` | `Demo123!` | One pharmacy |

Use **Settings → Reset demo data** to restore the starting state between runs. **Settings → Simulate a page load error** makes the next page show its error and Retry state.

## Requirements

User stories and acceptance criteria live on the Jira board **KM (Katalian MedSource)**.

## Hosting

Deployed on Render as a static site using `render.yaml`. No build step: Render serves `index.html` from the repo root.

## Test automation

Interactive elements carry `data-testid` attributes for stable locators.
