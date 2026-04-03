# Report vs Updated Notebook

This is a quick side-by-side comparison between:

- the sector allocation story described in [`resprojreport (4).pdf`](/Users/koroushemari/Documents/thesis/resprojreport%20(4).pdf)
- the current global-scope Python notebook outputs in [`top_sector_allocations.csv`](/Users/koroushemari/Documents/thesis/outputs/python_allocation/top_sector_allocations.csv)

| Scenario | Report emphasis | Updated notebook top allocations | Match quality |
|---|---|---|---|
| DAPS | Wind, Non-metallic minerals, Hydro electric, Biomass Solid | CO2 Capture, Land transport, Nuclear | Weak |
| DiRe | Advanced Electric Appliances, Crude Oil, Hydrogen, Warehousing | Land transport, Nuclear, Advanced Electric Appliances | Partial |
| HWTP | Clean Gas, Biomass, EV Transport Equipment | EV Transport Equipment, Wind, Biofuels, Biomass, PV | Moderate / best match |
| SWUC | Computer/Electronics, Oil/Coal-fired names, Batteries, Renewables | CO2 Capture, Land transport, Nuclear, Advanced Electric Appliances, Batteries | Weak to partial |

## Current notebook summary

| Scenario | Mean PD | Allocated mean PD | Top allocated sector |
|---|---:|---:|---|
| DAPS | 0.276365 | 0.245463 | CO2 Capture |
| DiRe | 0.275805 | 0.247087 | Land transport |
| HWTP | 0.263143 | 0.150113 | EV Transport Equipment |
| SWUC | 0.284875 | 0.249238 | CO2 Capture |

## Takeaway

The updated notebook is internally cleaner than the report-style prototype, but it only matches the report narrative well for `HWTP`. The other scenarios still do not separate strongly enough at the sector-allocation level.
