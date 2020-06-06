# README.md

- author : Sylvie Dagoret-Campagne
- creation date : may 2020
- update : June 6nd 2020

Work on resolution in transverse focal plane


## Extract from Ray beams the spot plot and produce summary file

- DrawPSF.ipynb	 : depracated
- DrawPSF.ipynb	 : deprecated
- DrawPSF_v3.ipynb : circular beam	


## Show resolution in a summary plot
- DrawResolution.ipynb : deprecated
- DrawResolution_v2.ipynb : read summary file from DrawPSF_XX.ipynb and do plots
- DrawResolution_FWHM.ipynb : use FWHM instead of sigma

## Work on FWHM / CTIO Data and Optical simulation comparison for article

- CorrectImage.ipynb


## Resampling of beam for PSF

### Compute beam resampling
- DrawInterpolatedPSF.ipynb : deprecated, better use the script in **../scripts/ResampleBeamRays.py**

### Analyse the resampled beam from python script in **../scripts/ResampleBeamRays.py**

- AnaInterpolatedPSF.ipynb	 : wavelength by wavelength

- AnaInterpolatedPSFMultiWL.ipynb	 : 4 wavelenght alltogether
	
