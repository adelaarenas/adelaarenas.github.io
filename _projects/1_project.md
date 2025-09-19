---
layout: page
title: Detector Calibration 
description: An Internship Project - Calibration of NaI(Tl) Scintillation Detector
img: assets/img/1.jpg
importance: 3
category: work
---

As part of my internship at the Philippine Nuclear Research Institute (PNRI), I conducted an energy and efficiency calibration of a sodium iodide (NaI(Tl)) scintillation detector using standard gamma-ray sources Cobalt-60 (Co-60) and Cesium-137 (Cs-137). 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/co-60-energy-spectrum.png" title="Co-60 Energy Spectrume" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cs-137-energy-spectrum.png" title="Cs-137 Energy Spectrum" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Counts vs energy Spectra of Co-60 (left) and Cs-137 (right) measured using a NaI(Tl) scintillation detector.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/energy-channel-curve.png" title="Energy Calibration Curve" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/fepe-curve.png" title="FEPE Curve" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Energy (left) and Full-Energy Peak Efficiency (right) calibration curves of the NaI(Tl) scintillation detector derived from Co-60 and Cs-137 standard sources.
</div>

Radiation detectors do not “know” the exact energy of radiation they see since they only produce signals as electrical pulses. To interpret these signals, we need to **calibrate** the detector. This is similar to teaching a thermometer what "0°C" and "100°C" mean using ice and boiling water.  

Each radioactive source emits photons at very specific energies (Cs-137 at ~662 keV, Co-60 at ~1173 and ~1332 keV). The detector detects these as counts and designates the detected intensity of the energy on bins aka channels that constitute the spectrum. By plotting known energies vs. observed channel numbers, I performed a **regression analysis** to find the best fit equation for the energy and efficiency of the detector.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/NaI-detector.png" title="NaI Detector" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This is the detector used for this project and my undergraduate research.
</div>

