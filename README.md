# Khair | خير

**Khair** is an Arabic prototype platform designed to organize the rescue of surplus edible food by connecting restaurants and stores with charities capable of collecting and distributing it. The project aims to reduce food waste and facilitate tracking donations from posting the offer to recording its impact.

> **Project Status:** An interactive front-end interface for experimentation and demonstration. Accounts, offers, requests, and reports are saved locally in the browser using `localStorage`; there is no backend service, database, or real authentication.

## Features

* Responsive Arabic interface with Right-to-Left (RTL) layout.
* Create a demo profile for a restaurant, store, or charity organization.
* Post a surplus offer including food type, quantity, city, address, readiness time, pickup deadline, storage method, and allergen information.
* Browse offers, search, and filter them by city and food type, and sort results by expiration date, posting date, or quantity.
* Request to reserve a quantity and specify an estimated arrival time, followed by request approval, and tracking delivery, pickup, and distribution.
* Demo dashboards for donors and charities, along with an impact log and statistics.
* Submit a report on an offer and review it from a demo management page.
* Hide expired or closed offers from the available offers list.

## Website Pages

* **Home:** Introduction to the platform and steps for contribution.
* **Available Offers:** Search, filter, and browse surplus food.
* **Dashboard:** Track offers and requests according to account type.
* **Impact Log:** Completed operations and explanatory statistics.
* **About Khair:** Vision, workflow, and shared responsibility.
* **Platform Management:** Review reports within the demo model.

## Donation Workflow

1. The donor creates a demo profile and posts an offer with food details and pickup times.
2. The charity browses the offers, requests the quantity it can collect, and specifies its arrival time.
3. The donor reviews and accepts the request, then records the handover of the food.
4. The charity confirms receipt and can record whether the food has been distributed to beneficiaries.
5. The completed donation appears in the impact log, and the data saved in the browser is updated.

## Running Locally

1. Download the project files or extract `khair-public-site.zip`.
2. Open `index.html` in a modern web browser.
3. Try creating a donor or charity account, then add an offer and request a reservation.

The prototype requires no package installations or build tool setups. The site files can also be hosted on a static page hosting service to display the demo online. Opening the site from another device or browser will not transfer the locally saved data.

## Project Files

* `index.html` — Site structure and page content.
* `styles.css` — Colors, layout, responsiveness, and RTL support.
* `app.js` — Demo data, navigation, demo accounts, search, booking, and status tracking.
* `khair-logo.svg` & `khair-logo.png` — Full logo in SVG and PNG formats.
* `khair-mark.svg` & `khair-mark.png` — Short icon/mark in SVG and PNG formats.
* `khair-brand-notes.md` — Visual identity notes.
* `khair-public-site.zip` — Website file package for publishing or sharing.

## Production and Real-World Usage

The files can be hosted as a static page to showcase the demo, but this does not turn it into a shared operational service. Before receiving real donations, the project will need a server, a database, secure login and account permissions, image storage, notifications, procedures for reviewing accounts and reports, and appropriate privacy policies and terms of use.

In this prototype, the platform only organizes food offers and reservations. The donor remains responsible for describing the food and its condition accurately, and the charity must adhere to the agreed-upon collection and storage conditions as well as applicable food safety requirements.

The site may require an internet connection to load Google Fonts; system fonts are used as a fallback if the connection drops.
