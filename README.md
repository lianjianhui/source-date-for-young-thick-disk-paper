# source-date-for-young-thick-disk-paper
Collection of processed data for young thick disk work

This repository includes the processed data that are presented in Lian et al. 2025 () in which we discover a young thick disk component in the Milky Way galaxy. The structure of the files are as following:

data_fig2_lowa-higha-integrated: Scale height as a function of radius for the integrated low- and high-$\alpha$ populations as shown in Figure 2 in the paper. Dimensions in (2,14,2). First dimension is the two populations in an order of high-alpha and low-alpha. Second dimension is radius, with radial range from 0 to 14 kpc with even interval of 1kpc. The last dimension represents the properties and associated uncertainties of the two populations at each radii, including average Galactocentric radius (kpc), scale height (kpc), scale height uncertainty (kpc).  

data_fig2_lowa-MAPs: the same structure of data_fig2_lowa-higha-integrated.fits file but includes the scale height for the mono-abunance populations (MAPs) in the low-$\alpha$ sequence. 

data_fig5l: Scale height of MAPs in the solar radius as a function of age color-coded by [Fe/H] as shown in the left panel of Figure 3 in the paper. Dimensions in (12,17,3). First dimension is [Mg/Fe] from -0.1 to 0.5 with step of 0.05. Second dimension is [Fe/H] from -1.1 to 0.6 with step of 0.1. Third dimension includes the properties of each MAP along the young and old age-[Fe/H] sequences (see the definition in the paper), in an order of age (Gyr), [Fe/H], scale height (kpc) of the MAPs on the old sequence and of the MAPs on the young sequence. 

data_fig5r: Vertical velocity dispersion of MAPs in the solar radius as a function of age color-coded by [Fe/H] as shown in the right panel of Figure 3 in the paper. Dimensions in (12,17,3). First and second dimensions are the same as data_fig3l. Third dimension includes the properties of each MAP along the young and old age-[Fe/H] sequences (see the definition in the paper), in an order of age (Gyr), [Fe/H], velocity dispersion (km/s) of the MAPs on the old sequence and of the MAPs on the young sequence. 

The APOGEE sample is selected from APOGEE DR17 (https://data.sdss.org/sas/dr17/apogee/spectro/aspcap/dr17/synspec_rev1/allStar-dr17-synspec_rev1.fits) with age and distance measurement taken from the astroNN value-added catalog (https://data.sdss.org/sas/dr17/env/APOGEE_ASTRO_NN/). 
