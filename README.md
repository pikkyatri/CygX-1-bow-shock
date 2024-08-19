# CygX-1-bow-shock
This repository contains code for analysing the bow shock detected near the Cyg X-1 black hole X-ray binary. It also includes codes for all figures made in Atri et al. 202x. 
1) CygX-1_bow-shock_parameters.ipynb uses the measured parameters of the bowshock in L, S and Halpha band as inputs to estimate the bowshock exapansion velocity, average jet power that is fueling the bowshock and the bowshock age. It also creates the plot that has been used as Figure 6 in the paper.
2) Plot_contours_bowshock_Lband.ipynb imports the calibrated L-band image fits files to create intensity maps, contour plots and bowshock zoom-in as has beeen marked in Figure 1 and 2 of the paper.
3) Plot_contours_bowshock_Sband.ipynb imports the calibrated S-band image fits files to create intensity maps, contour plots and bowshock zoom-in as has beeen marked in Figure 3 and 4 of the paper.
4) Spectral_map.ipynb calcualtes the spectral index and its error per pixel between the L and S-band MeerKAT intensity map. The S-band and L-band beamsizes are the same. The code has created the plots used in Figure 5 and Appendix figure 1 in the paper.



### Requirements

To run the codes, you need the following packages for the scripts:

## CygX-1_bow-shock_parameters.ipynb

- **Python**: `3.6`
- **Astropy**: `4.0.2`
- **Matplotlib**: `3.3.4`
- **Numpy**: `1.19.5`
- **Scipy**: `1.5.3`
- **Seaborn**: `0.11.2`
- **Pandas**: `1.1.5`
- **Joblib**: `0.13.2`

## Plot_contours_bowshock_Lband.ipynb

- **Python**: `3.6`
- **Astropy**: `4.0.2`
- **Matplotlib**: `3.3.4`
- **Aplpy**: `2.0.3`
- **Numpy**: `1.19.5`

## Plot_contours_bowshock_Sband.ipynb

- **Python**: `3.6`
- **Astropy**: `4.0.2`
- **Matplotlib**: `3.3.4`
- **Aplpy**: `2.0.3`
- **Numpy**: `1.19.5`

## Spectral_map.ipynb

- **Python**: `3.6`
- **Astropy**: `4.0.2`
- **Matplotlib**: `3.3.4`
- **Aplpy**: `2.0.3`
- **Numpy**: `1.19.5`

