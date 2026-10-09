# AquaCore FCDI Engineering Lab v2

Static, Vercel-ready research dashboard for Team AquaNova (University of Ilorin).

## What it does
- Models conventional and fish-gill-inspired FCDI with equal membrane area and operating conditions.
- Runs a 60-control-volume simplified steady-state NaCl salt balance, equivalent electrical resistance, and parallel-plate hydraulic pressure drop.
- Searches gill branch count and feed gap to improve a conditional salt-transfer-per-energy objective, with constraints.
- Exports comparison data and an explicit methodology text file.

## Critical scientific status
**This is an unvalidated reduced-order numerical screening model, not COMSOL, CFD, an experimentally validated FCDI model, or measured AquaCore performance.** Many material and geometry assumptions are illustrative. The geometry advantage is not guaranteed; the optimizer cannot be interpreted as physical proof. Compare against published experimental data and implement calibrated 3D ion transport and CFD before making quantitative performance claims.

## Deployment
Upload `index.html` and `README.md` to a new GitHub repository. In Vercel choose **Add New > Project**, import the repo, set framework **Other**, no build command, deploy. Existing AquaCore site need not be changed.

## References
- Mishra et al., *Desalination* (2026): https://www.sciencedirect.com/science/article/pii/S0011916425010501
- Shi et al., *Water Research* (2023): https://www.sciencedirect.com/science/article/pii/S0043135422014622
- Tubular FCDI CFD (2021): https://www.sciencedirect.com/science/article/pii/S0043135421006965