# Threat Actor Database

An open-source intelligence (OSINT) research tool for analyzing and visualizing designated terrorist and extremist organizations. Built as a demonstration of applied intelligence analysis workflows — combining structured data, network analysis, and geospatial visualization in a single analyst-facing interface.

> **Disclaimer:** All data is sourced exclusively from publicly available reporting, government designations, and academic literature. This project is intended for educational and portfolio purposes only.

---

## Overview

This application simulates the kind of structured threat actor tracking used by intelligence analysts and law enforcement. It is designed to mirror real analytical workflows: organizing raw information into structured profiles, mapping affiliate networks, and identifying geographic areas of operation.

Key analytical features:
- **Structured profiles** — standardized fields across all organizations (founding, status, ideology, threat level, funding, notable operations, designations)
- **Affiliate network graph** — D3 force-directed visualization of inter-organizational relationships
- **Geospatial mapping** — Leaflet-based map of active regions of operation per organization
- **Filtering and search** — real-time filtering by ideology category and keyword

---

## Motivation

During my internship at the NJ Transit Police Intelligence Unit, I worked with structured intelligence products — BOLOs, bulletins, and analytical reports — that required organizing disparate open-source information into clear, actionable formats. This project extends that experience into a web environment, applying the same analytical discipline to a publicly documented dataset.

It also reflects my broader interest in how emerging technologies can support the intelligence cycle — particularly in the collection, processing, and presentation phases.

---

## Tech Stack

- **React** (Vite)
- **D3.js** — force-directed network graph
- **Leaflet.js** — geospatial mapping with CartoDB dark tiles
- Custom CSS — no UI component libraries

---

## Data Sources

All organization data is drawn from publicly available sources including:
- U.S. State Department Foreign Terrorist Organization (FTO) designations
- UN Security Council Consolidated Sanctions List
- EU Terrorist List (Common Foreign & Security Policy)
- Stanford Mapping Militants Project
- START (National Consortium for the Study of Terrorism) database

---

## Running Locally

```bash
npm install
npm run dev
```

---

## Author

C
