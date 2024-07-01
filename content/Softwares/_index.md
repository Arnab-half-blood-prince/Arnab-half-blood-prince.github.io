+++
title = "Software"
template = "simple-section.html"
+++


### 21cm data analysis
I contribute to [radiocosmology](https://github.com/radiocosmology) suite of codes for simulation and analysis of data from transit radio interferometers.

The main software packages within [radiocosmology](https://github.com/radiocosmology), I have made contributions to:

- [draco](https://github.com/radiocosmology/draco/) is a Python package that contains
the pipeline building blocks for analysis of the data from general transit radio
interferometers. It is built upon the pipeline framework in

- [driftscan](https://github.com/radiocosmology/driftscan/) is a Python package for
modelling the transfer function of transit telescopes, and generating the derived
products needed to filter out foregrounds and estimate the power spectrum of 21 cm data.
- [cora](https://github.com/radiocosmology/cora/) is a Python package for generating
simulations of the low-frequency radio sky with a focus on polarised synchrotron
foregrounds from both our own galaxy and point sources, and cosmological 21 cm signal.

### GMRT data analysis pipeline

The analysis pipeline to calibrate and flag RFI of GMRT data, which I developed during my Ph.D is public and can be found here [GMRT_DI_Calibration_pipeline](https://github.com/Arnab-half-blood-prince/GMRT_DI_Calibration_pipeline)

This pipeline will do a Direction-Independent calibration of  uGMRT data along with RFI flagging. I have tested this to Band 3 (250 - 500 MHz), Band 4 (550-850 MHz) and Band 5 (1050-1450 MHz) uGMRT data.
