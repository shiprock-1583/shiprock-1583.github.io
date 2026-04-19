---
layout: single
permalink: /research/
title: "Research"
author_profile: true
---
### Integral Vorticity Balance for Arctic Mediterranean Ocean Circulation
<p align="center">
 <img width="60%" src="/images/Fig4_abcdef_djf_jja_Lh-Ty_0-400m_iolnormTrue.png">
    <br>
    <span style="font-size:0.65em;"><em>Zonal-mean seasonal-mean patterns of OTA, Truth and Predictions.</em> </span>
</p>

### Deep Learning of Systematic Data Assimilation Increments in the Ocean
<p align="center">
 <img width="60%" src="/images/Fig4_abcdef_djf_jja_Lh-Ty_0-400m_iolnormTrue.png">
    <br>
    <span style="font-size:0.65em;"><em>Zonal-mean seasonal-mean patterns of OTA, Truth and Predictions.</em> </span>
</p>
<span style="font-size:0.75em;"> As a part of an industry-funded multi-institutional project, I developed and evaluated a neural network-based technique to correct systematic model errors in an ocean component of the coupled general circulation model. The method relies on the fact that data assimilation (DA) increments in an ensemble-based DA system encapsulate errors arising from deficiencies in fast physics, dynamics, and numerics, which can be learned by neural networks (NNs). In this work, the DA increments are derived from the GFDL’s SPEAR-ODA system (Seamless  System for Prediction and EArth System Research-Ocean Data  Assimilation), which assimilates observed sea surface temperature and vertical profiles of temperature and salinity from the Argo dataset. I trained and evaluated NNs of different sizes and architectures, using predictors including local stratification, shears, and surface fluxes. Neural networks can capture up to 40-50% of the daily variance in temperature increments in the upper 20 m relative to the benchmark’s 20%. Despite being column-local and lacking geographical inputs, networks can reproduce spatial patterns at daily and longer timescales. The patterns consist of corrections to regional dynamical features such as western boundary currents, equatorial undercurrents, bathymetry-related corrections in the Southern Ocean, and warm surface increments over subtropical and midlatitude belts. The figure above compares predicted zonal-mean corrections across the two seasons with the truth and a benchmark. These local, state-dependent neural networks form the basis for data-driven model-error parameterization and bias-correction techniques. </span>

### Mechanisms of Arctic Freshwater Variability and its impacts
<p align="center">
 <img width="60%" src="/images/Picture3.png">
    <br>
    <span style="font-size:0.65em;"><em>Circulation in the freshwater layer and its changes.</em> </span>
</p>

<span style="font-size:0.75em;"> The Arctic Ocean has accumulated significant amounts of liquid freshwater over the past two decades. It remains an outstanding question to what extent the increase can be attributed to anthropogenically forced changes rather than to natural climate variability. In this study, we investigated the mechanisms of Arctic freshwater variability using a large ensemble of fully coupled climate model simulations and an observationally forced ocean-sea ice simulation within the Community Earth System Model (CESM) framework. We found that the thinning of the Arctic sea ice is largely anthropogenically forced and primarily contributes to the recent freshening of the Arctic Ocean. The climate system's natural variability strongly influences gateway freshwater transports via changes in ocean circulation and affects the spatial distribution of the increase, moving it from the Eurasian into the Canadian basin, thereby inflating freshwater in the Beaufort Gyre as illustrated in the figure above. </span>

<span style="font-size:0.75em;"> In a related ocean modeling study, we tracked freshwater from the Beaufort Gyre and quantified its impact on the North Atlantic's salinity. We found that during 1983-1995, the freshwater released from the Beaufort Gyre crossed the Canadian Arctic Archipelago and Davis Strait before freshening up the Labrador Sea by ~0.2 psu. In collaboration with NCAR, I assessed the hindcast skill of an initialized decadal prediction large ensemble in predicting observed variations in the Arctic freshwater content. Such predictions often suffer from systematic errors called initialization-induced decadal drift. I worked on developing a new dynamical drift correction technique that removes bias and improves predictive performance compared to currently used methods. </span>

### Deep Learning of Subpolar North Atlantic SST
<p align="center">
 <img width="60%" src="/images/Picture1.png">
    <br>
    <span style="font-size:0.65em;"><em>Skill comparison as a function of lead time in months.</em> </span>
</p>
<span style="font-size:0.75em;">As part of an internal LANL grant sponsored by the Center for Space and Earth Science, I developed a deep learning model to forecast high-latitude climate variability on seasonal to interannual timescales. We investigated physical processes that provide predictability across different timescales and studied the benefits of using deep learning over traditional statistical approaches. For this purpose, a convolutional neural network is used to predict subpolar North Atlantic Sea Surface Temperature (SST) from prior SST and upper ocean heat content fields. The training and testing data were obtained from a long preindustrial control simulation with the CESM. The results were compared against autoregressive and (spatially extended) linear inverse models as benchmarks, as shown in the figure above. </span>

### Climate Extremes and Tropical Ocean Dynamical Response to Sulfate Aerosols  
<p align="center">
 <img width="75%" src="/images/Picture2.png">
    <br>
    <span style="font-size:0.65em;"><em>Transient Atmospheric Response to Sulfate Aerosol Forcing.</em> </span>
</p>
<span style="font-size:0.75em;"> My Ph.D. thesis includes i) investigating the effect of sea surface temperature and synoptic variability on climate extremes over the continental United States, and ii) investigating aerosols' impact on tropical climate using the hierarchy of CESM simulations. In the first part, the remote effects of SST interannual variability on precipitation and temperature extremes over the United States were studied through a series of sensitivity experiments with the Weather Research and Forecasting (WRF) model. The impact of propagating synoptic disturbances on the simulated mean state was also studied by changing the western lateral boundary conditions. The second part was carried out in collaboration with the Oak Ridge National Laboratory. I studied coupled ocean-atmosphere processes over the tropical Pacific and how anthropogenic sulfate aerosols affect them. The possibility of sulfate emissions from Asia as a potential source of seasonal-interannual predictability through its impact on ENSO dynamics was explored in this work. The changes in large-scale atmospheric circulation and associated precipitation changes are illustrated in the figure above. </span>
