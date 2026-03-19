# MTF — From Optics to Measurement

Every optical system introduces a blur. Not only because of a defect but because of physics.
This notebook series explains how to quantify it, measure it, and understand where it comes from.

The **Modulation Transfer Function (MTF)** is the universal metric for imaging sharpness.
The same framework applies to satellite sensors, cinema lenses, MRI scanners, and smartphone cameras.

## What's inside

**`MTF_01_fundamentals.ipynb`**  
PSF, OTF, slanted edge pipeline (ISO 12233), and the numerical traps that affect every MTF estimate in practice: truncation, spectral leakage, windowing bias, noise propagation.

**`MTF_02_earth_observation.ipynb`** *(in progress)*  
EO-specific contributors: optics, pixel integration, jitter, smear, forward linear motion.
Applied to real Sentinel-2 imagery.

## Built on

numpy · scipy · matplotlib

---

*Part of an open image quality toolbox for Earth Observation.*  
*Full toolbox and consulting — [floragabriagues.github.io](https://floragabriagues.github.io)*
