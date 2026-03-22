# 🚛 CDL Transit & HOS Calculator (FMCSA 2026 Compliant)

Professional logistics tool designed to estimate real-world Transit Time (ETA) for OTR (Over-the-Road) operations, factoring in mandatory safety regulations and driver types.

## 🌟 Key Features
* **Live Road Distance:** Calculates actual highway miles using the OSRM (Open Source Routing Machine) engine.
* **HOS Logic (2026 Regulations):** Automatically calculates:
    * **Solo Drivers:** 11-hour driving limit, 8-hour break rule (30 min), and 10-hour mandatory resets.
    * **Team Drivers:** Continuous operation logic for long-haul routes (>800 miles) with mandatory switch-off breaks.
* **Automated ETA:** Provides a clear breakdown of "Net Drive Time" vs. "Total Transit Time."
* **Professional Branding:** Integrated with PepsiCo Transportation Services (PTS) visual standards.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Responsive Design).
* **Logic:** Vanilla JavaScript (ES6+).
* **APIs:** * *Nominatim* for Geocoding (City to Coordinates).
    * *OSRM* for Road Network Routing.

## 📋 How it Works
The calculator assumes a conservative professional average of **52 mph**. This accounts for pre-trip inspections, fuel stops, and typical interstate traffic, providing a realistic "Planner's View" rather than just a theoretical GPS time.

## 👤 Author
**Eduardo Lopez** *Supply Chain Planner | Logistics Automation Enthusiast* 📧 [eduardo.lopez1@pepsico.com](mailto:eduardo.lopez1@pepsico.com)

---
*Disclaimer: This tool is intended for planning estimates. Actual driver logs must comply with ELD recorded data.*
