
# 4f Phase Contrast Optical System

This directory contains analytical and numerical implementations of a 4f phase contrast optical system. The tasks explores phase contrast imaging using Fourier filtering techniques and aims to visualize and analyze transparent objects through phase manipulation as a part of graduate level optics course assignment.

## Features

### Analytical Tasks
1. **Fourier Plane Field Analysis**:
   - Derive expressions for the field in the Fourier plane using Taylor series expansions.
   - Determine peak locations in the Fourier domain.
2. **Phase Mask Analysis**:
   - Analyze the effect of a phase mask on the imaging plane field and irradiance.
   - Calculate image contrast with and without the phase mask.

### Numerical Simulations
1. **Phase Contrast Imaging**:
   - Use a digital photograph as input for phase contrast simulation.
   - Apply hypergaussian apertures to simulate realistic lens effects.
   - Render Fourier transform magnitudes and filtered images.
2. **Fourier Filtering**:
   - Implement and analyze phase filters ($\phi = \pi/2$ and $\phi = 0$) and compute resulting contrasts.
   - Explore optimal filter parameters for achieving maximum contrast.
3. **High-Pass Filtering**:
   - Simulate and analyze the effect of a high-pass amplitude filter in the Fourier plane.
   - Visualize the transformation from low to high frequencies as the filter parameter varies.

## Content
- **Tasks**: Problem descriptions and requirements for analytical derivations and numerical experiments are available in file `4f_Phase_Contrast_Optical_System_Tasks.pdf`.
- **Code**: Python notebook for analytical calculations and numerical simulations and visualizations of the 4f system is avaialble as `4f_Phase_Contrast_Optical_System.ipynb` - Only code for task 2 and latter are available since task 1 is theoretical derivation part and its solution is included  in `Task1_solution.pdf`.