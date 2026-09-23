# IE Carbon Footprint Calculator

**Status: prototype.** A branded, source-cited personal carbon footprint
calculator built for IE University's sustainability initiative.

## What it does

Estimates a user's annual carbon footprint across six categories —
campus commute, flights, housing & energy, diet, consumption, and
waste — through a single-page form, and returns a breakdown with the
source cited for every emission factor used.

## Emission factors & sources

- **Transport:** UK DEFRA 2023
- **Flights:** ICAO Carbon Calculator (split by short/medium/long haul)
- **Energy:** IEA 2023, Spain grid factor
- **Diet:** Poore & Nemecek (2018), *Science*
- **Consumption:** Ellen MacArthur Foundation; Apple/Dell environmental reports
- **Waste:** EPA WARM Model; WRAP Food Waste Study

Estimated accuracy: ±20–25%, comparable to WWF and UN carbon calculators.

## Tech

Single-file HTML/CSS/JS. No backend, no build step, no dependencies
beyond the Montserrat webfont.

---
Built by [Luchi López Noriega](https://github.com/thislucha)
