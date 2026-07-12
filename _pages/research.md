---
title: "Research"
permalink: /research/
author_profile: true
---

My research sits at the intersection of climate dynamics, tropical meteorology, and machine learning. I am broadly interested in understanding how the climate system responds to natural and anthropogenic forcing, with a focus on extreme weather events — particularly tropical cyclones.

---

## Climate Model Biases and SST Patterns

A persistent challenge in climate science is that coupled climate models often misrepresent sea surface temperature (SST) patterns — most notably the "double-ITCZ" bias and the associated warm bias in the eastern Pacific cold tongue. My work investigates how these biases distort the simulated climate response to external forcing (e.g., aerosol reductions, Antarctic ozone depletion), and develops flux adjustment techniques to correct them.

**Key questions:** How do SST pattern biases shape the response to greenhouse gas forcing and aerosol changes? Can we use flux adjustment to produce more realistic climate simulations?

**Related projects:**
- Flux adjustment of CESM2 → [cesm2-fa](https://github.com/jingyizhuo/CESM2-FA)
- Eastern Pacific cooling under aerosol reduction *(Under review)*
- Muted eastern Pacific cooling linked to double-ITCZ bias *(In prep)*

---

## Tropical Cyclone Activity under Climate Change

Understanding how tropical cyclone (TC) frequency, intensity, and hazard respond to both natural variability and long-term warming is central to climate risk assessment. I study how SST warming patterns — whether from model bias or real-world forcing — modulate TC activity, and re-examine historical TC frequency trends using improved observational methods.

**Key questions:** How do SST warming patterns affect TC hazard? What do the historical trends in TC frequency really look like when observational heterogeneities are accounted for?

**Related projects:**
- SST warming pattern biases and TC activity *(Under review)*
- Re-examining historical TC frequency trends — [Jones et al., GRL 2026](https://doi.org/10.1029/2026GL122083)
- TC hazard response to natural and forced warming — [Lin et al., npj 2025](https://doi.org/10.1038/s41612-025-00997-y)
- SST patterns on TCs → [cesm2-fa_tc](https://github.com/jingyizhuo/CESM2-FA_TC/tree/main)

---

## Physics-Informed Machine Learning for Tropical Cyclones

Satellite imagery offers a continuous, global record of TC structure, but translating raw imagery into reliable intensity and size estimates remains difficult. I develop deep learning models that incorporate physical constraints to improve these estimates, and apply them to build long, homogeneous datasets of TC inner-to-outer size.

**Key questions:** How can we encode physical knowledge into neural networks to improve TC monitoring? What do multi-decadal records of TC size reveal about long-term trends?

**Related projects:**
- Real-time TC monitoring → [deeptcnet](https://forecast.nju.edu.cn/deeptcnet) *(operational at China National Satellite Meteorological Center)*
- 37-year TC size dataset → [deeptcsize](https://forecast.nju.edu.cn/deeptcnet/dataset.html)
- Physics-augmented deep learning for TC intensity/size — [Zhuo & Tan, MWR 2021](https://doi.org/10.1175/MWR-D-20-0333.1)
- TC size trends from deep learning reconstruction — [Zhuo & Tan, J. Climate 2023](https://doi.org/10.1175/JCLI-D-22-0714.1)
- Eye detection for improved intensity estimation — [Liu et al., JRA-ML 2026](https://doi.org/10.1029/2025JH000816)
- Diurnal pulsing signatures for AI-driven intensity prediction — [Zhang et al., GRL 2026](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2025GL119496)
