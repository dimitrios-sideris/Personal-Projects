# Personal Projects

This repository contains validation results (plots and case definitions) for literature models implemented from the literature.  
**Code may be provided upon request.**

## Contents
- `models/`: validation folders per literature model
- `references/`: BibTeX and links to original publications

## Scope
Validation focuses on comparing model predictions against published results (e.g., conversion, selectivity, yield, and/or profiles) under reported operating conditions.

## What is included
- Validation plots (parity plots, trends vs operating conditions, profiles)
- Case definitions (operating conditions, feeds, parameters where publicly available)
- Notes on assumptions and any data digitization

## What is not included
- Source code, solver implementation, or proprietary datasets

## Models
| Model folder | Publication | Notes |
|---|---|---|
| `models/<key>/` | Author et al., Year (DOI link) | Reactor type, key outputs |

## How to interpret the plots
- Parity plots: model vs literature values
- Trend plots: selectivity/conversion vs T, P, WHSV, etc.
- Profiles: axial/time profiles where applicable

## Citation
Please cite the original publications listed in `references/`.  
If you use this repository, you may cite it via `CITATION.cff`.

## License
The plots and text in this repository are licensed under <your license here>.  
Original publications remain under their respective copyrights.
