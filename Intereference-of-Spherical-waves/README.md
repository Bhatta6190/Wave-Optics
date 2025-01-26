
# Exact Interference of Spherical Waves

This directory contains code to compute and render amplitude ($|E(x, y, z)|$) and phase ($\Phi(x, y, z)$) distributions of monochromatic spherical waves. The electric field is given by:

$\
E(x, y, z) = \sum_{j=1}^N \frac{A_j}{r_j} e^{i(kr_j + \phi_j)},
\$
where $r_j = \sqrt{(x - x_j)^2 + (y - y_j)^2 + z^2}$.

## Tasks
1. **Three Sources in Circular Arrangement**  
   - $N = 3$, $z = 1000\lambda$, pixel size $\Delta x = \Delta y = \lambda$, grid $1024 \times 1024$.  
   - Cases:  
     (a) $a = 10\lambda$,  
     (b) $a = 30\lambda$.  

2. **Two Sources Along X-Axis**  
   - $N = 2$, $z = 1000\lambda$, $x_1 = -a$, $x_2 = a$, $y_1 = y_2 = 0$.  
   - Cases:  
     (d) $a = 10\lambda$,  
     (e) $a = 30\lambda$.  

3. **Amplitude Variation with Distance**  
   - Explore $|E(x, y, z)|$ for different $z$, from near-field to far-field.

4. **Plane Wave Representation**  
   - Identify which far-field patterns correspond to 3 plane waves:
     $$
     |E| \sim \left| \sum_{j=1}^3 e^{i(k_{x,j}x + k_{y,j}y)} \right|,
     $$
     where $k_{x,j} = \frac{2\pi}{\lambda} \frac{x_j}{z}$, $k_{y,j} = \frac{2\pi}{\lambda} \frac{y_j}{z}$.
