# Cork City Hotel — Booking Application
**Full-stack coursework case study · Node.js · Express · EJS · MySQL**

A hotel booking prototype I built during my computing studies. The application connects a server-rendered booking flow to a MySQL room table, with supporting HTML/CSS/JavaScript pages.

## The problem

A visitor needs to browse available room categories, select dates and room quantities, and understand an estimated booking total.

## How I approached it

```text
Room selection / date input
             ↓
Express application + EJS views
             ↓
MySQL room catalogue
             ↓
Booking state + cost calculation
             ↓
Demo login → confirmation page
```

### Features in the coursework

- A server-rendered hotel website with room information.
- A MySQL-backed room catalogue and selectable room types.
- Date, quantity and total-cost handling across the booking journey.
- A session-backed confirmation flow and example login.
- A separate date/time and optional weather-information page.

### Technologies

Node.js, Express, EJS templates, MySQL, HTML, CSS and JavaScript. The original application also integrated an external weather API.

## What I'd improve for production

This was designed as **coursework**, not a deployed hotel product. I would strengthen input validation, date and availability rules, account security, session configuration, error handling, automated tests and dependency maintenance. A real booking platform would additionally need payment handling and transactional inventory management.

## Source availability

The coursework source has been separated from bundled `node_modules` and hard-coded service credentials in a **cleaned project archive**. It has not been published here as a complete repository: the original student project includes illustrative photographs whose redistribution rights have not yet been verified. An end-to-end production or deployment test has not been claimed.

---

[Return to portfolio](../README.md)
