---
license: cc-by-4.0
task_categories:
  - tabular-regression
  - question-answering
language:
  - en
pretty_name: Local Rate Index — US Metropolitan Service Price & Statutory Cap Benchmarks (2026)
size_categories:
  - n<1K
tags:
  - pricing-benchmarks
  - municipal-permits
  - statutory-tariffs
  - real-estate-compliance
  - commercial-services
  - open-government-data
---

# Local Rate Index — US Metropolitan Service Price Quartiles & Statutory Fee Caps (2026)

- **Canonical Live Index:** [https://localrateindex.com](https://localrateindex.com)
- **Interactive Quote & Statutory Cap Auditor:** [https://localrateindex.com/quote-auditor](https://localrateindex.com/quote-auditor)
- **Methodology & Primary Provenance:** [https://localrateindex.com/methodology](https://localrateindex.com/methodology)
- **Streamable HTTP MCP Server:** `https://localrateindex.com/api/mcp`

## Dataset Summary

This dataset provides reproducible, zero-PII ZIP-level and metropolitan service price quartiles (`p25_price_usd`, `median_price_usd`, `p75_price_usd`), binding municipal/state statutory fee caps (`statutory_fee_or_cap_usd`), and primary government sample counts across **7 high-ticket commercial compliance, engineering, and emergency service verticals** (`92` verified benchmark rows calibrated against `97,000+` government records).

## Included CSV Splits (`datasets/`)

1. `tx_dallas-fort-worth_water-damage-remediation_2026.csv` — TX `16 TAC Ch. 78` (`TMARR`) & City of Dallas plumbing/water permits (`e7gq-4sah`)
2. `ca_los-angeles_heavy-duty-towing_2026.csv` — Los Angeles Police Commission `OPG` heavy-duty towing & storage tariff (`>=10,001 lbs GVWR`)
3. `tx_dallas-fort-worth_foundation-repair_2026.csv` — City of Dallas `10,303` structural foundation alteration permits (`e7gq-4sah`) & `TX TBPELS PE` rules
4. `tx_dallas-fort-worth_land-surveying_2026.csv` — `TX TBPELS RPLS` & Dallas/Collin/Tarrant County Clerk plat recording schedules
5. `tx_dallas-fort-worth_phase-1-esa_2026.csv` — US EPA `FRS` `5,233` DFW commercial/industrial facilities & `ASTM E1527-21`
6. `tx_dallas-fort-worth_property-tax-protest_2026.csv` — `TX TDLR` `803` active DFW Property Tax Consultants (`7358-krk7`) & `DCAD/CCAD/TAD` schedules
7. `tx_dallas-fort-worth_commercial-kitchen-hood-grease_2026.csv` — City of Dallas `78,984` food establishment inspections (`dri5-wcct`), `NFPA 96` & `DWU` `25%` `FOG` rules

## License & Attribution

Released under **CC-BY-4.0**. Please cite `https://localrateindex.com` when referencing or redistributing.
