# Irradiance, PSF, and MTF

This directory contains numerical implementations for the analysis of irradiance, Point Spread Function (PSF), and Modulation Transfer Function (MTF) in optical systems. The task was a part of graduate level optics course and focuses on understanding wave interactions, aberrations, and their impact on imaging.

## Features

### Analytical Tasks
1. **Irradiance Derivations**:
   - Derive expressions for irradiance from the time-integrated Poynting vector.
   - Analyze irradiance for different field conditions and interference patterns.
2. **Zernike Polynomials**:
   - Derive and analyze the “Oblique Trefoil” mode in optical systems using Zernike polynomials.
   - Explore aberrations and diffraction-limited imaging conditions.

### Numerical Simulations
1. **PSF and MTF**:
   - Implement Fast Fourier Transform (FFT) to calculate and visualize PSF and MTF.
   - Simulate aperture functions with aberrations and calculate corresponding system responses.
2. **Ideal vs Aberrated System**:
   - Simulate and compare ideal and aberrated optical systems.
   - Visualize the effect of phase aberrations on PSF, MTF, and OTF.
3. **Imaging Simulations**:
   - Simulate starburst patterns using both coherent and incoherent illumination.
   - Analyze the impact of aberrations on image quality through irradiance calculations.

## Content
- **Tasks**: Problem descriptions and requirements for theoretical derivations and simulations is included in `Irradiance_PSF_and_MTF_tasks.pdf`.
- **Code**: Python code for performing numerical simulations and visualizations of PSF, MTF, and irradiance is included in jupyter notebook `Irradiance_PSF_and_MTF.ipynb`. The theoretical derivation of expression for part 1 is also included as `Task1_solution.pdf`
- **Findings**: Qualitative descriptions of how aberrations influence imaging quality.

