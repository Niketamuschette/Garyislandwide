# Garyislandwide
# Garyislandwide AC Management App ❄️📋🧾

A mobile-first progressive web application built specifically for AC installation, repair, and servicing technicians. It combines a robust **Client Management Book**, automated **Quote Reminders**, an **AC Unit & Logistics Quote Calculator**, and an interactive **PDF & WhatsApp Invoice Creator**.

---

## 🚀 Key Features

* **📋 Client Book & Pipeline Management:** 
  * Keep track of customer contact information, site addresses, job types, appointment dates, and account balances.
  * Interactive filter chips to instantly isolate clients by status: *All, Quote due, Appointments, Not started, Started, Unpaid,* and *Paid*.
  * Built-in quick action links for one-tap **SMS** or **WhatsApp** follow-ups and appointment confirmations.
* **⏰ Quote & Schedule Reminders:**
  * Automatically flags overdue or upcoming quote follow-ups so you never miss a lead.
* **🧮 AC Unit & Logistics Quote Calculator:**
  * Instantly computes estimated costs based on standard inverter and non-inverter BTU units (12k to 36k BTU), installation labor, and extra logistics/transport fees.
  * Includes a direct button to forward estimates straight to clients via WhatsApp.
* **🧾 Professional Invoice Creator:**
  * Pulls client data directly from your saved database.
  * Add custom itemized materials, quantities, sizes, and adjustable local sales taxes.
  * Generates clean breakdown totals including deposits paid and final balance due.
  * One-click **Download PDF Invoice** (leveraging native browser print/PDF export) or send formatted itemized summaries instantly via **WhatsApp**.
* **☁️ Flexible Data Storage:**
  * Operates seamlessly using local device storage (`localStorage`) or hooks directly into **Firebase Firestore** for real-time cloud synchronization across your phone, tablet, and computer.

---

## 🛠️ Technology Stack

* **Frontend:** Vanilla JavaScript (ES6 Modules), HTML5, CSS3 (Modern custom properties, CSS Grid/Flexbox, fully responsive layout tailored for mobile screens and safe-area-insets).
* **Backend / Database:** Google Firebase Firestore (`v10.8.0`).
* **Fonts:** Google Fonts (*Barlow*, *Barlow Condensed*, *IBM Plex Mono*).

---

## 📱 Mobile-First Optimization

The application is completely optimized for mobile browser use:
* **Touch-Friendly UI:** Large tap targets and streamlined layouts prevent misclicks on smartphones.
* **PWA Ready:** Open the webpage in your mobile browser (Safari on iOS or Chrome on Android) and tap **"Add to Home Screen"** to run it like a native app.
* **Smart Phone Formatting:** Automatically handles local phone numbers (such as formatting Jamaican numbers to ensure direct integration with `wa.me` chat links).

---

## 🚀 Getting Started / Installation

1. Save your application code into a single file named `index.html`.
2. Host it on any static hosting provider (such as GitHub Pages, Netlify, Vercel, or Firebase Hosting) or open `index.html` directly inside any modern web browser.
3. The app will automatically connect to Firebase Cloud storage using your configured credentials or fall back gracefully to local browser storage if offline.
