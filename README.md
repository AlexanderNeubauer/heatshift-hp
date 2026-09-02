# HeatShift-HP

**Code release in preparation — the full source code, bundled datasets, and
documentation will be published in this repository within the next days.**

HeatShift-HP is an open-source Python/Modelica co-simulation workflow for
assessing the techno-economic load-shifting potential of heat pump systems
with central hot-water thermal storage under dynamic electricity tariffs and
grid fees. It couples a generic air-to-water heat pump and stratified-storage
plant model (FMI 2.0 Co-Simulation FMU) with guarded rule-based supervisory
controllers and time series of weather, heating load, and end-user
electricity prices.

The upcoming release contains the complete simulation framework, the
Modelica plant model, all input datasets, the full 576-case parameter-study
result table underlying the paper's tables and figures, analysis scripts,
and three worked example notebooks — verified to reproduce the paper's
results section from the bundled data without a Modelica tool or commercial
licence.

## Companion article

Alexander Neubauer, Oliver Awasthi-Hilgendorf, Peter Grant, Tianzhen Hong,
Yannick Fürst, Stefan Brandt, Martin Kriegel:
**HeatShift-HP: A Techno-Economic Framework for Assessing Heat Pump Load
Shifting under Dynamic Tariffs and Grid Fees.**
*Energy and Buildings*, 118164 (2026).
<https://doi.org/10.1016/j.enbuild.2026.118164>

```bibtex
@article{NEUBAUER2026118164,
  title   = {HeatShift-HP: A Techno-Economic Framework for Assessing Heat
             Pump Load Shifting under Dynamic Tariffs and Grid Fees},
  journal = {Energy and Buildings},
  pages   = {118164},
  year    = {2026},
  issn    = {0378-7788},
  doi     = {10.1016/j.enbuild.2026.118164},
  author  = {Alexander Neubauer and Oliver Awasthi-Hilgendorf and Peter
             Grant and Tianzhen Hong and Yannick F{\"u}rst and Stefan
             Brandt and Martin Kriegel},
}
```

## Licence and contact

The code will be released under the MIT licence (see `LICENSE`).
Contact: Alexander Neubauer, Hermann Rietschel Institute, TU Berlin —
<a.neubauer@tu-berlin.de>

## Acknowledgements

This work is funded by the German Federal Ministry for Economic Affairs and
Energy (BMWE) in the framework of the research program EnOB:ML-EBESR
03EN1076B. The support is gratefully acknowledged. The author gratefully
acknowledges Lawrence Berkeley National Laboratory for hosting a research
stay during which parts of this manuscript were prepared.
