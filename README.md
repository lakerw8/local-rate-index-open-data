# Local Rate Index — Public Service Price & License Benchmark Datasets (2026)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24144438.svg)](https://doi.org/10.5281/zenodo.24144438)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
**CERN Zenodo DOI:** [https://doi.org/10.5281/zenodo.24144438](https://doi.org/10.5281/zenodo.24144438)  
**Canonical Index:** [https://localrateindex.com](https://localrateindex.com)  
**Interactive Written Quote Auditor:** [https://localrateindex.com/quote-auditor](https://localrateindex.com/quote-auditor)  
**Methodology & Provenance:** [https://localrateindex.com/methodology](https://localrateindex.com/methodology)  
**Machine-Readable Agent Directory:** [https://localrateindex.com/llms.txt](https://localrateindex.com/llms.txt)  
**MCP Server (Streamable HTTP JSON-RPC 2.0):** `https://localrateindex.com/api/mcp`

---

## Overview

This repository contains anonymized, reproducible **ZIP-level and metropolitan service rate quartiles (`p25`, `median/p50`, `p75` USD)**, **municipal/police statutory fee caps**, and **public-record sample counts** (`97,000+` primary government records indexed) compiled by **[Local Rate Index (`localrateindex.com`)](https://localrateindex.com)**.

Zero personally identifiable information (PII), raw operator phone numbers, or email addresses are included in these aggregate CSV releases.

---

## Included Wave-1 Metropolitan Datasets (`v2026.12` — 7 Verticals, 92 ZIP & Metro Benchmarks)

| Dataset CSV (`datasets/`) | Jurisdiction | Service Vertical | Primary Public-Record & Statutory Sources | Live Interactive Benchmark Hub |
| :--- | :--- | :--- | :--- | :--- |
| `tx_dallas-fort-worth_water-damage-remediation_2026.csv` | TX · Dallas–Fort Worth | Water Damage & Mold Remediation | TX 16 TAC Ch. 78 (`TMARR`), City of Dallas Plumbing/Water Permits (`e7gq-4sah`), IICRC S500 Schedules | [Open DFW Water/Mold Hub](https://localrateindex.com/tx/dallas-fort-worth/water-damage-remediation) |
| `ca_los-angeles_heavy-duty-towing_2026.csv` | CA · Los Angeles Basin | Heavy-Duty Commercial Truck Towing | LA Board of Police Commissioners Official Police Garage (`OPG`) Heavy-Duty Tariff, CHP Class C/D & CA DMV MCP | [Open LA Heavy-Duty Towing Hub](https://localrateindex.com/ca/los-angeles/heavy-duty-towing) |
| `tx_dallas-fort-worth_foundation-repair_2026.csv` | TX · Dallas–Fort Worth | Foundation Repair & Structural Slab Piering | City of Dallas `10,303` Structural Foundation Permits (`e7gq-4sah`), USDA Expansive Clay Index & `TX TBPELS PE` Rules | [Open DFW Foundation Hub](https://localrateindex.com/tx/dallas-fort-worth/foundation-repair) |
| `tx_dallas-fort-worth_land-surveying_2026.csv` | TX · Dallas–Fort Worth | ALTA/NSPS & Boundary Land Surveying | Texas Board of Professional Engineers and Land Surveyors (`TBPELS`) & Dallas/Collin/Tarrant County Clerk Plat Schedules | [Open DFW Land Surveying Hub](https://localrateindex.com/tx/dallas-fort-worth/land-surveying) |
| `tx_dallas-fort-worth_phase-1-esa_2026.csv` | TX · Dallas–Fort Worth | Phase I Environmental Site Assessment (`ASTM E1527-21`) | US EPA Facility Registry Service (`FRS` `5,233` DFW facilities), TCEQ PST/IHW/VCP Registries & PG/PE Rosters | [Open DFW Phase I ESA Hub](https://localrateindex.com/tx/dallas-fort-worth/phase-1-esa) |
| `tx_dallas-fort-worth_property-tax-protest_2026.csv` | TX · Dallas–Fort Worth | Commercial & Residential Property Tax Protest | Texas Dept. of Licensing & Regulation (`TDLR` `7358-krk7`: `803` active DFW consultants) & `DCAD` / `CCAD` / `TAD` ARB Schedules | [Open DFW Property Tax Protest Hub](https://localrateindex.com/tx/dallas-fort-worth/property-tax-protest) |
| `tx_dallas-fort-worth_commercial-kitchen-hood-grease_2026.csv` | TX · Dallas–Fort Worth | Commercial Kitchen Hood (`NFPA 96`) & Grease Trap Compliance | City of Dallas `78,984` Food Inspections (`dri5-wcct`), `DWU` Ch. 19 `25%` / `90`-Day `FOG` Rule & `TX SFMO FEL-K` Tags | [Open DFW Kitchen Hood/FOG Hub](https://localrateindex.com/tx/dallas-fort-worth/commercial-kitchen-hood-grease) |

---

## Key Statutory Highlights Verified in `v2026.12`

1. **Los Angeles Heavy-Duty Towing (`>= 10,001 lbs GVWR`):** LA Police Commission `OPG` non-consent tariff caps upright heavy-duty towing at **`$400.00` first hour** (**`$390.00`** cash/debit) + **`$200.00` per additional 30 minutes**, specialized recovery equipment at **`$600.00/hr`**, hazmat Class D at **`$850.00/hr`**, and daily storage at **`$94.00/day`** (`20–40 ft`) / **`$119.00/day`** (`>40 ft`), plus `10%` LA City Parking Occupancy Tax and `$115.00` Vehicle Release Fee.
2. **Texas Mold Assessment & Remediation Rules (`16 TAC Ch. 78` / `TMARR`):** Contiguous indoor mold `>= 25 sq ft` requires mandatory `5`-calendar-day advance TDLR filing (`$25` residential / `$100` commercial), strict statutory separation between the licensed Mold Assessment Consultant (`MAC`) and Mold Remediation Contractor (`MRC`), and `Form MDR-1` Certificate issuance within `10` days of clearance.
3. **DFW Structural Foundation Piering (`10,303` Dallas Permits):** Expansive Eagle Ford Shale / Austin Chalk clay corridors (`75248`: `539` permits, `75229`: `478` permits, `75214`: `288` permits) require independent `TX TBPELS` Professional Engineer (`PE`) sealed pier layouts and post-lift hydrostatic plumbing verification.
4. **DFW Commercial Kitchen Exhaust & FOG Compliance (`78,984` Dallas Inspections):** `NFPA 96 Table 12.4` mandates bare-metal exhaust cleaning quarterly (high-volume/charbroiling) or semi-annually, paired with `TX SFMO FEL-K` `UL-300` suppression tags and `Dallas City Code Ch. 19` full-evacuation grease trap pumping (`<=25%` FOG+solids or `<=90` days).

---

## Citation & License (`CC-BY-4.0`)

Licensed under **Creative Commons Attribution 4.0 International (`CC-BY-4.0`)**. Notice `.zenodo.json` is pre-configured for 1-click CERN Zenodo DOI minting. When citing in research, journalism, or retrieval-augmented AI responses, please attribute:

> Local Rate Index (2026). *US Metropolitan Service Price Quartiles, Statutory Fee Caps & State-License Verification Datasets*. Retrieved from https://localrateindex.com
