# Alumina Nanoparticle Optical Property Data

This repository contains raw and processed optical property data for **alumina (Al₂O₃) nanoparticles**, including measurements from:

- Complex refractive index calculations
- Photoacoustic spectrometry (PAS)
- Electron energy loss spectroscopy (EELS)

---

## Files Included

### 1. `Alumina_Refractive_Index_1nm.csv`
- **Description**: Complex refractive index (`n` and `k`) at **1 nm resolution**
- **Wavelength Range**: 10 nm to 100,000 nm
- **Columns**:
  1. `Wavelength (nm)`
  2. `n` — real part of refractive index
  3. `k` — imaginary part of refractive index
  4. `k_25%` — 25% interquartile value of `k`
  5. `k_75%` — 75% interquartile value of `k`

---

### 2. `Alumina_Refractive_Index_PAS.csv`
- **Description**: PAS-derived imaginary part of refractive index (`k`) values at selected visible and near-IR wavelengths
- **Wavelengths**: 375, 405, 532, 721, 1047 nm
- **Columns**:
  1. `Particle Type` — Spherical alpha-phase, Irregular alpha-phase, Irregular gamma-phase
  2. `Wavelength (nm)`
  3. `n_points` — Number of data points
  4. `k_25%` — First quartile
  5. `k_median` — Median value
  6. `k_75%` — 75th percentile
  7. `k_lower_bound` — Tukey lower bound
  8. `k_upper_bound` — Tukey upper bound

---

### 3. `Alumina_Refractive_Index_EELS.csv`
- **Description**: Imaginary refractive index (`k`) from **EELS measurements** on multiple nanoparticles
- **Wavelength Range**: 27 nm to 1375 nm
- **Columns**:
  1. `Wavelength (nm)`
  2. `k_1` to `k_10` — Individual measurements from 10 ROIs

---
## License
This dataset is dedicated to the public domain under the [Creative Commons CC0 1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/).  
You may copy, modify, distribute, and use the data — **even for commercial purposes — without asking permission**.

---

## References

1. Tropf, W. J., and M. E. Thomas (1998), Aluminum oxide (Al2O3) revisited, in Handbook of Optical Constants of Solids, vol. 3, pp. 653–677, Academic Press, New York.
2. 
