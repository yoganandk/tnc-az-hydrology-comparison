# Comparing Hydrologic/Hydraulic Modeling Techniques for Drainage Design in Arizona

Funded by **The Nature Conservancy** | June 2023  
**Yoganand Korgaonkar**, Assistant Professor of Practice  
School of Geography, Development & Environment, University of Arizona

---

## Overview

This project compares three hydrologic/hydraulic modeling tools — the AGWA Urban Tool, EPA SWMM, and HEC-HMS — for their ability to estimate urban enhanced runoff in addition to peak flows in an urban watershed. The study was motivated by a need to evaluate whether tools used by Arizona's Regional Flood Control Districts can support green infrastructure planning and groundwater recharge estimation.

## Models Compared

| Model | Developer | License |
|---|---|---|
| AGWA Urban Tool (KINEROS2) | USDA-ARS / University of Arizona | Free (request) |
| EPA SWMM | US EPA / CDM Smith | Free, open source |
| HEC-HMS | US Army Corps of Engineers | Free |

## Case Study

**Site:** La Terraza subdivision, Sierra Vista, Arizona (14 ha, 66 residential lots)  
**Event:** 100-year, 2-hour precipitation event (2.89 inches, NOAA Atlas 14)  
**Scenarios:** Predevelopment and postdevelopment

## Repository Structure
```
├── report/         # Final project report
├── models/
│   ├── agwa/       # AGWA Urban Tool project files
│   ├── swmm/       # EPA SWMM project files
│   └── hec-hms/    # HEC-HMS project files
├── results/        # Output tables and hydrographs
├── assets/         # Website styles and scripts
├── images/         # Website images and figures
└── index.html      # Project website (GitHub Pages)
```

## Key Findings

- All three models can estimate urban enhanced runoff, though with notable differences in methodology and results.
- AGWA and HEC-HMS use kinematic wave equations; SWMM uses non-linear reservoir routing, producing significantly different pre/post development runoff ratios.
- AGWA Urban Tool offers the most streamlined GIS-integrated workflow for parcel-scale urban modeling.

## Acknowledgements

This research was funded by The Nature Conservancy. Special thanks to Holly Richter and Kimberly Schonek (TNC) and Juliet McKenna (Montgomery & Associates).

## License

MIT — see [LICENSE](LICENSE)