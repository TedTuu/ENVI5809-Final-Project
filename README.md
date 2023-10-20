Run in binder: https://mybinder.org/v2/gh/shannonbohman/Final-Project/master

# ENVI5809-Final-Project
the Thermal Limitation of Seagrasses in Great Barrier Reef Ecosystem

# Data: 
We use three dataset in the eReef database:
- https://thredds.ereefs.aims.gov.au/thredds/dodsC/GBR4_H2p0_B3p1_Cq3b_Dhnd/monthly.nc
- http://thredds.ereefs.aims.gov.au/thredds/dodsC/s3://aims-ereefs-public-prod/derived/ncaggregate/ereefs/GBR4_H2p0_B3p1_Cq3b_Dhnd/daily-monthly/EREEFS_AIMS-CSIRO_GBR4_H2p0_B3p1_Cq3b_Dhnd_bgc_daily-monthly-2019-01
- http://thredds.ereefs.aims.gov.au/thredds/dodsC/s3://aims-ereefs-public-prod/derived/ncaggregate/ereefs/gbr4_v2/daily-monthly/EREEFS_AIMS-CSIRO_gbr4_v2_hydro_daily-monthly-2019-01

The meaning of the model name of GBR4_H2p0_B3p1_Cq3b_Dhnd: 
- GBR4: Great Barrier Reef model with a grid of approximately 4 kilometres resolution.
- H2p0: Hydrodynamic model version 2.0
- B3p1: Biogeochemical model version 3.1
- Cq3b: Catchment model using load specification q3b. P2R SOURCE Catchments with 2019 catchment condition from Dec 1, 2010 - 30/6/2018 (used for GBR Report Card 8 published in 2019), Empirical SOURCE with 2019 catchment  condition, Jul 1, 2018 - April 30, 2019.
- Dhnd: Model deployment - Hindcast

This project uses the datasets with the following variables:
- water depth (zc, meter)
- date (time, day-month-year)
- pH (PH, log(mM))
- temperature (temp, degrees Celcius)
- current speed and direction (mean_cur, ms-1)

# Planned analysis: 

Figure 1 shows a basemap of the area considered in this project using cartopy.

Figure 2 investigates seasonal variability in the BoB by taking temporal means of SSH and SST across the different seasons.

Figure 3 investigates the relationship between mixed layer depth and SSH.

Figure 4 investigates the propagation of SSH anomalies, ultimately finding velocity.

Figure 5 shows a basemap of the area considered in this project using cartopy.

Figure 6 investigates seasonal variability in the BoB by taking temporal means of SSH and SST across the different seasons.

Figure 7 investigates the relationship between mixed layer depth and SSH.

Figure 8 investigates the propagation of SSH anomalies, ultimately finding velocity.
