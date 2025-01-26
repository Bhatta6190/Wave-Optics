# Beam Propagation Method

## Description
This directory contains the implementation of tasks related to the Beam Propagation Method (BPM) for a graduate-level optics course. The tasks included the following:

1. **Point Spread Function of a Circular Aperture**  
   - Computation and visualization of the point spread function (PSF) using a 2D Fast Fourier Transform (FFT).
   - Grayscale image rendering of the aperture's electric field and its FFT transformations.  
   - Determination of the pixel distance between the peak and the first minimum of the PSF.

2. **Resolving Two Point Objects**  
   - Analysis of the Rayleigh resolution criterion by calculating the interference of two tilted plane waves at the aperture.
   - Visualization of the combined intensity and reporting the angle of tilt, φ, satisfying the criterion.

3. **Beam Propagation**  
   - Implementation of the BPM to propagate a Gaussian beam in the near-field regime for various distances (z < zd).  
   - Visualization of the field magnitude and phase for five different propagation distances.

4. **Spot of Arago**  
   - Simulation of light propagation through an annular aperture to observe the formation of the Poisson spot (Spot of Arago).  
   - Determination of the propagation distance at which the spot forms and its relation to the diffraction parameter zd.

## Features
- Python implementations of 2D FFT and BPM.
- Grayscale and HSV colormap visualizations of electric fields and phase distributions.
- Scripts to calculate Rayleigh resolution, PSF, and Poisson spot formation.

## Contents
- **Code**: Scripts for all tasks and results is available in python jupyter notebook `Beam_Propagation_Method.ipynb`.
- **Resources**: Task instructions included in `BPM.pdf` and other reference materials available are: `BPM4b_paraxial.pdf` and `BPM4b_paraxial.pdf` file.

