# 🌿 Green Guardian — Civic Cleanliness AI App

> Built in 24 hours at **Hack the Waste 2026** — an international online hackathon hosted by HackTribe for the **City of Leuven, Belgium**.

[![Hackathon](https://img.shields.io/badge/Hack%20the%20Waste-May%202026-green)](https://hacktribe.co)
[![Certificate](https://img.shields.io/badge/Certificate-4a99de4f-teal)](https://hacktribe.co)
[![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JavaScript-blue)]()

---

## 🏆 Hackathon Context

| Detail | Info |
|--------|------|
| **Event** | Hack the Waste — 24-hour online hackathon |
| **Dates** | 8–9 May 2026 |
| **Challenge** | Generate a solution to the cleanliness challenge provided by the City of Leuven |
| **Team** | International, cross-disciplinary — teams from Belgium, South Africa, Brazil, Germany, and the Netherlands |
| **Certificate ID** | `4a99de4f-04a6-4442-ab48-aa09b717e891` |
| **Organisers** | HackTribe · Belgium Campus iTversity · UCLL · THU · UNESP · BA School of Business and Finance · City of Leuven |

---

## 🎯 What It Does

Green Guardian is a **mobile-first web application** that allows Leuven city residents and cleanup teams to collaboratively manage street cleanliness. It works as a full citizen-to-city reporting pipeline — from spotting litter to marking an area cleaned.

### Core Features

| Feature | Description |
|---------|-------------|
| 📍 **Live GPS Heatmap** | Real-time Leaflet.js map showing reported waste zones as coloured overlays (red = high risk, yellow = medium, green = low/cleaned) |
| 🤖 **AI Waste Scanner** | Uploads a photo and runs AI classification to identify waste type (plastic, organic, hazardous, etc.) and assign an urgency score out of 100 |
| 📸 **Photo Evidence Upload** | Attach image evidence to each report — stored with the record and visible in the tracking view |
| 🔁 **Duplicate Detection** | Detects if a new report is within 50m of an existing one and prompts the user to confirm or merge |
| 🗂️ **Report Management** | Full list of active and cleaned reports with status tracking and timeline |
| 👷 **Admin Panel** | Cleanup team assignment (Team Alpha / Bravo / Charlie) per report, with status updates |
| ✅ **Cleaning Confirmation** | Mark reports as cleaned — heatmap zone turns green, report moves to history |
| 🔐 **User Authentication** | Login/session flow with citizen and admin roles |

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (CSS Variables, responsive layout), Vanilla JavaScript (ES6+)
- **Mapping:** [Leaflet.js](https://leafletjs.com/) with OpenStreetMap tiles
- **AI Integration:** Gemini API (AI waste classification and urgency scoring)
- **Storage:** Browser localStorage for report persistence across sessions
- **Architecture:** Single-file SPA (`index.html`) — screen-based navigation with no page reloads

---

## 📱 App Screens

```
Login → Splash / Dashboard
       ├── Heatmap (live GPS map with coloured waste zones)
       ├── New Report (GPS attach + photo upload + AI scan)
       │         └── AI Results screen
       ├── Reports List (active / cleaned)
       │         └── Report Tracking (timeline + map link)
       └── Admin Panel (assign cleanup teams + mark cleaned)
           └── Feedback / Cleaned confirmation
```

---

## 🚀 Running Locally

No build step required. Open `index.html` directly in any modern browser.

```bash
git clone https://github.com/MasokaKarabo10/Green-Guardian
cd Green-Guardian
# Open index.html in your browser
```

> **Note:** GPS features require browser location permission. AI scanning requires a valid Gemini API key (enter via the in-app settings).

---

## 📂 Project Structure

```
index.html          # Entire application (HTML + embedded CSS + JS)
README.md           # This file
certificate.pdf     # Hack the Waste 2026 certificate of completion
```

---

## 🌍 International Collaboration

This project was built in a 24-hour window with an international, cross-disciplinary team. The challenge was provided by the **City of Leuven, Belgium**, requiring a real, deployable solution rather than a concept. The team combined perspectives from software engineering, business strategy, and civic design.

---

## 👤 My Contribution

- Built the full frontend application (HTML structure, CSS design system, all JavaScript logic)
- Implemented the Leaflet.js heatmap with GPS zone rendering and report-to-map linking
- Built the AI scanning flow (photo upload → API call → results display)
- Implemented duplicate detection, admin panel, and cleaning workflow
- Developed the go-to-market strategy and business case document for the solution

---

## 📜 Certificate

**Certificate of Completion** — Hack the Waste, 24-hour online hackathon  
Awarded to: **Karabo Masoka**  
Date: 2026-05-12  
ID: `4a99de4f-04a6-4442-ab48-aa09b717e891`  
Generated via [HackTribe.co](https://hacktribe.co)

---

*Built under pressure. Shipped in 24 hours.*
