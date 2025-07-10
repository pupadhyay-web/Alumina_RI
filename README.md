# Alumina_RI
This repository contains raw and processed optical property data for alumina (Al₂O₃) nanoparticles, 
including the complex refractive index, 
photoacoustic spectrometry (PAS), 
and electron energy loss spectroscopy (EELS) measurements.

Alumina_Refractive_Index_1nm.csv
  Description: Complex refractive index (n and k) at 1 nm resolution.
  Wavelength range: 10 nm to 100,000 nm.
  Columns:
	1. Wavelength (nm)
	2. n — real part of refractive index
	3. k — imaginary part of refractive index
  4. k - 25% Interquatile value of refractive index
  5. k - 75% Interquatile value of refractive index

Alumina_Refractive_Index_PAS.csv
  Description: PAS-derived imaginary part of refractive index (k) values at selected visible and near-IR wavelengths.
	Wavelengths: 375, 405, 532, 721, 1047 nm
	Columns:
	1. Particle Type — Spherical alpha-phase, Irregular alpha-phase, Irregular gamma-phase 
	2. Wavelength (nm)
  3. Number of data points
	4. k_25% — first quartile
	5. k_median
	6. k_75%
	7. k_lower_bound
	8. k_upper_bound

Alumina_Refractive_Index_EELS.csv
  Description: Imaginary refractive index (k) from EELS measurements on multiple nanoparticles.
	Wavelength range: 27 nm to 1375 nm
	Columns:
	1. Wavelength (nm)
	2. k_1 to k_10 — individual measurements
