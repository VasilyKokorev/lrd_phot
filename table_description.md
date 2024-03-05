## Notes

- Flux densities and uncertainties were corrected to total and are given in units of ``microJansky`` (AB zeropoint = 23.9).
- Pixel scale of original images is 0.04"/pixel 
- Photometry **is not** corrected for Galactic extinctions
- Missing data (e.g., filter coverage doesn't overlap) indicated with flux/error ``-99``.

## Table Columns


|                   *Column*     |                                                                                        *Description* |
|     :--------------------:     |                                                         :------------------------------------------- |
|                                |                          |
| ``id``| Object Identifier|
| ``field``| Field where the object is located|
| ``ra``| Right Ascension|
| ``dec``| Declination|
| ``{filter}_flux``| Total flux density in a given HST or JWST filter, measured within D=0.36", uJy |
| ``{filter}_fluxerr``| Uncertainty on the total flux density in a given HST or JWST filter, measured within D=0.36", uJy |
| ``z_phot``| Best-fit photoz from EAZY|
| ``z_phot16``| 16th percentile of pdf(z) (1-sigma)|
| ``z_phot84``| 84th percentile of pdf(z) (1-sigma)|
| ``av``| Extinction in the V-band, ABmag |
| ``av_err``| Uncertainty on the extinction in the V-band, ABmag|
| ``lbol``| Dust corrected AGN bolometric luminosity, erg/s|
| ``lbol_err``| Uncertainty on the dust corrected AGN bolometric luminosity, erg/s|
| ``muv``| Observed UV (rest, 1450 AA) absolute magnitude, ABmag|
| ``muv``| Uncertainty on the observed UV (rest, 1450 AA) absolute magnitude, ABmag|
| ``r_eff_16_pix``| 16th percentile on the effective radius, pixels|
| ``r_eff_50_pix``| 50th percentile (median) on the effective radius, pixels|
| ``r_eff_84_pix``| 84th percentile on the effective radius, pixels|
| ``r_eff_16_phys``| 16th percentile on the physical effective radius, pc|
| ``r_eff_50_phys``| 50th percentile (median) on the physical effective radius, pc|
| ``r_eff_84_phys``| 84th percentile on the physical effective radius, pc|


