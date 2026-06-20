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
- Raw data from publications are extracted using WebPlotDigitizer

## What is not included
- Source code, solver implementation, Article documents

## Projects
| Project folder | Based on Publication | Project Name |
|---|---|---|
| Cordero-Lanzac CO<sub>2</sub> -to-Paraffins | Cordero-Lanzac et al. (2023), DOI: 10.1016/j.jcou.2022.102337 | Literature-Based Reactor Modeling for CO<sub>2</sub> Conversion to Hydrocarbons|

## Literature-Based Reactor Modeling for CO<sub>2</sub> Conversion to Hydrocarbons
The model describes the reaction of CO<sub>2</sub> and H<sub>2</sub> to light hydrocarbons (CH<sub>4</sub>, C<sub>2</sub>H<sub>6</sub>, C<sub>3</sub>H<sub>8</sub>, C<sub>4</sub>H<sub>10</sub>), occuring in a fixed bed, plug-flow reactor. 
The reactor is assumed to be 1D, isothermal, with negligible pressure losses.

Cordero-Lanzac et al. (2023), in their publication, they develop
a kinetic model for the direct, methanol-mediated conversion of CO<sub>2</sub>
to light hydrocarbons using a
PdZn/ZrO<sub>2</sub> + SAPO-34 tandem catalyst. The modeled reactor is assumed to be a steady-state,
packed-bed reactor with three layers, consisting of different mass ratios of metal oxides and zeolite.
The reaction network utilizes Langmuir-Hinshelwood reaction rates and includes 3 reversible reactions (rWGS & methanol synthesis from CO<sub>2</sub> and CO), and 4 (one-way) hydrogenation reactions for
the production of C<sub>1</sub>
-C<sub>4</sub> paraffins and water. Olefins are not included in the reaction scheme, because
they are assumed to react instantaneously over the Pd catalyst at pressurized H<sub>2</sub>
conditions.
