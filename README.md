# Electrical Sizing Data

Open datasets behind [Load & Watt](https://loadandwatt.com) — free home electrical calculators (wire size, voltage drop, generator sizing and more). Published so electricians, DIYers, students and developers can cite, reuse and build on the same numbers the calculators use.

## Files

**`nec-conductor-ampacity.csv`** — conductor sizes from 14 AWG to 500 kcmil: circular mils (NEC Chapter 9, Table 8) and ampacities at 75°C for copper and aluminum (NEC Table 310.16). The `small_conductor_limit` columns carry the NEC 240.4(D) overcurrent limits that apply to 14, 12 and 10 AWG regardless of the table ampacity.

**`eia-861-2025-residential-electricity-prices.csv`** — average residential electricity prices for all 50 states + DC, in cents per kWh. Source: US Energy Information Administration, Form EIA-861, final 2025 data (US average 17.23 ¢/kWh). These are annual state averages; a real bill differs by utility, plan and season.

## Notes

- The NEC is published by the NFPA and is copyrighted; the values here are factual reference data. Always confirm against the current NEC edition and your local amendments, and have a licensed electrician verify any real installation.
- EIA data is US federal public data.
- Spotted an error? Open an issue — corrections are verified against the sources above before merging.

## Use the calculators

Wire size, voltage drop, generator size, appliance running cost and 30+ more: https://loadandwatt.com

## Methodology

How these numbers are used, the formulas behind them, and how to check a result by hand: https://loadandwatt.com/methodology/
