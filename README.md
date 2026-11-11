# Local Rate Index — Public Service Price & License Benchmark Datasets (2026)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
**Canonical Index:** [https://localrateindex.com](https://localrateindex.com)  
**Machine-Readable Agent Directory:** [https://localrateindex.com/llms.txt](https://localrateindex.com/llms.txt)  
**MCP Server (Streamable HTTP JSON-RPC 2.0):** `https://localrateindex.com/api/mcp`

---

## Overview

This repository contains anonymized, reproducible **ZIP-level and metropolitan service rate quartiles (`p25`, `median/p50`, `p75` USD)**, **municipal/police statutory fee caps**, and **public-record sample counts** compiled by **[Local Rate Index (`localrateindex.com`)](https://localrateindex.com)**.

Zero personally identifiable information (PII), raw operator phone numbers, or email addresses are included in these aggregate CSV releases.

---

## Included Wave-1 Metropolitan Datasets (`2026`)

| Dataset CSV | Jurisdiction | Service Vertical | Primary Public-Record & Statutory Sources | Live Interactive Benchmark Hub |
| :--- | :--- | :--- | :--- | :--- |
| `tx_dallas-fort-worth_water-damage-remediation_2026.csv` | TX · Dallas–Fort Worth | Water Damage & Mold Remediation | TX 16 TAC Ch. 78 (`TMARR`), City of Dallas Plumbing/Water Permits (`e7gq-4sah`), IICRC S500 Schedules | [Open DFW Water/Mold Hub](https://localrateindex.com/tx/dallas-fort-worth/water-damage-remediation) |
| `ca_los-angeles_heavy-duty-towing_2026.csv` | CA · Los Angeles Basin | Heavy-Duty Commercial Truck Towing | LA Board of Police Commissioners Official Police Garage (`OPG`) Heavy-Duty Tariff, CHP Class C/D & CA DMV MCP | [Open LA Heavy-Duty Towing Hub](https://localrateindex.com/ca/los-angeles/heavy-duty-towing) |
| `tx_dallas-fort-worth_land-surveying_2026.csv` | TX · Dallas–Fort Worth | ALTA/NSPS & Boundary Land Surveying | Texas Board of Professional Engineers and Land Surveyors (`TBPELS`) & Dallas/Collin/Tarrant County Clerk Plat Schedules | [Open DFW Land Surveying Hub](https://localrateindex.com/tx/dallas-fort-worth/land-surveying) |
| `tx_dallas-fort-worth_phase-1-esa_2026.csv` | TX · Dallas–Fort Worth | Phase I Environmental Site Assessment (`ASTM E1527-21`) | US EPA Facility Registry Service (`FRS_PROGRAM_FACILITY`), TCEQ PST/IHW/VCP Registries & PG/PE Rosters | [Open DFW Phase I ESA Hub](https://localrateindex.com/tx/dallas-fort-worth/phase-1-esa) |
| `tx_dallas-fort-worth_property-tax-protest_2026.csv` | TX · Dallas–Fort Worth | Commercial & Residential Property Tax Protest | Texas Dept. of Licensing & Regulation (`TDLR` `7358-krk7`) & `DCAD` / `CCAD` / `TAD` ARB Hearing Schedules | [Open DFW Property Tax Protest Hub](https://localrateindex.com/tx/dallas-fort-worth/property-tax-protest) |

---

## Key Statutory Highlights Verified in 2026 Release

1. **Los Angeles Heavy-Duty Towing (`>= 10,001 lbs GVWR`):** Los Angeles Board of Police Commissioners `OPG` non-consent tariff caps upright heavy-duty towing at **`$400.00` first hour** (**`$390.00`** cash/debit) + **`$200.00` per additional 30 minutes**, specialized recovery equipment at **`$600.00/hr`**, hazmat Class D at **`$850.00/hr`**, and daily storage at **`$94.00/day`** (`20–40 ft`) / **`$119.00/day`** (`>40 ft`), plus `10%` LA City Parking Occupancy Tax and `$115.00` Vehicle Release Fee.
2. **Texas Mold Assessment & Remediation Rules (`16 TAC Ch. 78` / `TMARR`):** Contiguous indoor mold `>= 25 sq ft` requires mandatory `5`-calendar-day advance TDLR filing (`$25` residential / `$100` commercial), strict statutory separation between the licensed Mold Assessment Consultant (`MAC`) and Mold Remediation Contractor (`MRC`), and Certificate of Mold Damage Remediation (`Form MDR-1`) issuance within `10` days of post-remediation clearance.
3. **DFW Phase I Environmental Site Assessments (`ASTM E1527-21`):** Live US EPA `FRS` density across commercial DFW industrial corridors (`1,391` tracked facilities in `75034`, `592` in `75006`, `366` in `75247`) drives historical Recognized Environmental Condition (`REC`) review complexity and vapor-encroachment screening (`ASTM E2600`).

---

## Citation & License (`CC-BY-4.0`)

Licensed under **Creative Commons Attribution 4.0 International (`CC-BY-4.0`)**. When citing in research, journalism, or retrieval-augmented AI responses, please attribute:

> Local Rate Index (2026). *US Metropolitan Service Price Quartiles, Statutory Fee Caps & State-License Verification Datasets*. Retrieved from https://localrateindex.com
