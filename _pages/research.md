---
title: "Research"
permalink: /research/
layout: clean
---

My research sits at the intersection of climate dynamics, tropical meteorology, and machine learning. I am broadly interested in understanding how the climate system responds to natural and anthropogenic forcing, with a focus on extreme weather events — particularly tropical cyclones.

## Climate Model Biases and SST Patterns

A persistent challenge in climate science is that coupled climate models often misrepresent sea surface temperature (SST) patterns — most notably the "double-ITCZ" bias and the associated warm bias in the eastern Pacific cold tongue. My work investigates how these biases distort the simulated climate response to external forcing (e.g., aerosol reductions, Antarctic ozone depletion), and develops flux adjustment techniques to correct them.

<ul class="news-list">
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">Under review</span>
      <h3 class="news-title">Eastern Pacific Cooling due to Northern Hemisphere Aerosol Reduction, and the Role of Model Bias</h3>
      <p class="news-dek">How aerosol-driven cooling in the eastern Pacific is distorted by long-standing model SST biases, and what flux adjustment recovers.</p>
      <p class="news-byline">Zhuo, Lee, Vecchi, Seager, Sobel &amp; Camargo</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-sst.svg' | relative_url }}" alt="">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">In prep</span>
      <h3 class="news-title">A Muted Tropical Eastern Pacific Cooling Response to the Antarctic Ozone Hole, Linked to Double-ITCZ Bias</h3>
      <p class="news-dek">Tracing how the double-ITCZ bias mutes the simulated eastern Pacific response to Antarctic ozone depletion.</p>
      <p class="news-byline">Zhuo, Polvani &amp; Vecchi</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-sst.svg' | relative_url }}" alt="">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">J. Climate, 2025</span>
      <h3 class="news-title"><a href="https://doi.org/10.1175/JCLI-D-24-0331.1">A More La Niña–Like Response to Radiative Forcing after Flux Adjustment in CESM2</a></h3>
      <p class="news-dek">Correcting CESM2's mean-state SST bias with flux adjustment changes the model's forced response toward a more La Niña–like pattern.</p>
      <p class="news-byline">Zhuo, Lee, Sobel, Seager, Camargo, Lin, Fosu &amp; Reed</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-sst.svg' | relative_url }}" alt="">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">Code &amp; data</span>
      <h3 class="news-title"><a href="https://github.com/jingyizhuo/CESM2-FA">cesm2-fa</a></h3>
      <p class="news-dek">Flux adjustment implementation for the fully coupled climate model CESM2.</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-sst.svg' | relative_url }}" alt="">
  </li>
</ul>

## Tropical Cyclone Activity under Climate Change

Understanding how tropical cyclone (TC) frequency, intensity, and hazard respond to both natural variability and long-term warming is central to climate risk assessment. I study how SST warming patterns — whether from model bias or real-world forcing — modulate TC activity, and re-examine historical TC frequency trends using improved observational methods.

<ul class="news-list">
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">GRL, Under review</span>
      <h3 class="news-title">Impact of Sea Surface Temperature Trend Biases on Tropical Cyclone Activity and Hazard</h3>
      <p class="news-dek">How trend biases in simulated SST patterns propagate into projected tropical cyclone activity and hazard.</p>
      <p class="news-byline">Zhuo, Lee, Sobel, Camargo &amp; Vecchi</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-tc.svg' | relative_url }}" alt="">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">GRL, 2026</span>
      <h3 class="news-title"><a href="https://doi.org/10.1029/2026GL122083">Re-examining Historical Trends of Tropical Cyclone Frequency</a></h3>
      <p class="news-dek">Revisiting long-term TC frequency trends once observational heterogeneities across the record are accounted for.</p>
      <p class="news-byline">Jones, Zhuo, Camargo, Hodges, Bell &amp; Chand</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-tc.svg' | relative_url }}" alt="">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">npj Clim Atmos Sci, 2025</span>
      <h3 class="news-title"><a href="https://doi.org/10.1038/s41612-025-00997-y">The Response of Tropical Cyclone Hazard to Natural and Forced Patterns of Warming</a></h3>
      <p class="news-dek">Disentangling how natural and forced warming patterns each shape projected tropical cyclone hazard.</p>
      <p class="news-byline">Lin, Lee, Camargo, Sobel &amp; Zhuo</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-tc.svg' | relative_url }}" alt="">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">Code &amp; data</span>
      <h3 class="news-title"><a href="https://github.com/jingyizhuo/CESM2-FA_TC/tree/main">cesm2-fa_tc</a></h3>
      <p class="news-dek">Effects of corrected SST patterns on simulated tropical cyclone activity.</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-tc.svg' | relative_url }}" alt="">
  </li>
</ul>

## Physics-Informed Machine Learning for Tropical Cyclones

Satellite imagery offers a continuous, global record of TC structure, but translating raw imagery into reliable intensity and size estimates remains difficult. I develop deep learning models that incorporate physical constraints to improve these estimates, and apply them to build long, homogeneous datasets of TC inner-to-outer size.

<ul class="news-list">
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">Mon. Wea. Rev., 2021</span>
      <h3 class="news-title"><a href="https://doi.org/10.1175/MWR-D-20-0333.1">Physics-Augmented Deep Learning to Improve Tropical Cyclone Intensity and Size Estimation from Satellite Imagery</a></h3>
      <p class="news-dek">Injecting physical constraints into a CNN improves intensity and size estimates from IR satellite imagery; now used operationally by the China National Satellite Meteorological Center.</p>
      <p class="news-byline">Zhuo &amp; Tan</p>
    </div>
    <img class="news-thumb" src="{{ '/images/fig1_mwr2021.png' | relative_url }}" alt="Physics-augmented deep learning architecture for TC intensity and size estimation">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">J. Climate, 2023</span>
      <h3 class="news-title"><a href="https://doi.org/10.1175/JCLI-D-22-0714.1">A Deep-Learning Reconstruction of Tropical Cyclone Size Metrics (1981–2017): Examining Trends</a></h3>
      <p class="news-dek">A homogeneous 37-year record of TC inner-to-outer size, reconstructed with deep learning, used to examine long-term size trends.</p>
      <p class="news-byline">Zhuo &amp; Tan</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-ml.svg' | relative_url }}" alt="">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">JGR: Machine Learning and Computation, 2026</span>
      <h3 class="news-title"><a href="https://doi.org/10.1029/2025JH000816">Detection of Eye Occurrence in Sequential Satellite Infrared Imagery and Its Application to Improve Deep Learning-Based Tropical Cyclone Intensity Estimation</a></h3>
      <p class="news-dek">Detecting eye occurrence across image sequences sharpens deep-learning intensity estimates.</p>
      <p class="news-byline">Liu, Zhuo, Chu &amp; Tan</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-ml.svg' | relative_url }}" alt="">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">GRL, 2026</span>
      <h3 class="news-title"><a href="https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2025GL119496">Integrating Diurnal Pulsing Signatures for AI-Driven Tropical Cyclone Intensity Prediction</a></h3>
      <p class="news-dek">Diurnal pulsing signatures, folded into an AI model, improve short-term TC intensity prediction.</p>
      <p class="news-byline">Zhang, Zhuo, Guo, Zhu &amp; Tan</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-ml.svg' | relative_url }}" alt="">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">Open data, since 2021</span>
      <h3 class="news-title"><a href="https://forecast.nju.edu.cn/deeptcnet">deeptcnet</a></h3>
      <p class="news-dek">Real-time, deep learning–based tropical cyclone intensity and size monitoring.</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-ml.svg' | relative_url }}" alt="">
  </li>
  <li class="news-item">
    <div class="news-text">
      <span class="news-label">Open data</span>
      <h3 class="news-title"><a href="https://forecast.nju.edu.cn/deeptcnet/dataset.html">deeptcsize</a></h3>
      <p class="news-dek">A homogeneous 37-year dataset of tropical cyclone inner-to-outer size.</p>
    </div>
    <img class="news-thumb" src="{{ '/images/thumb-ml.svg' | relative_url }}" alt="">
  </li>
</ul>
