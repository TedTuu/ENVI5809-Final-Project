Run in binder: https://mybinder.org/v2/gh/shannonbohman/Final-Project/master

# ENVI5809-Final-Project
the Thermal Limitation of Seagrasses in Great Barrier Reef Ecosystem

# Data: 
We use three dataset in the eReef database:
https://thredds.ereefs.aims.gov.au/thredds/dodsC/GBR4_H2p0_B3p1_Cq3b_Dhnd/monthly.nc
http://thredds.ereefs.aims.gov.au/thredds/dodsC/s3://aims-ereefs-public-prod/derived/ncaggregate/ereefs/GBR4_H2p0_B3p1_Cq3b_Dhnd/daily-monthly/EREEFS_AIMS-CSIRO_GBR4_H2p0_B3p1_Cq3b_Dhnd_bgc_daily-monthly-
http://thredds.ereefs.aims.gov.au/thredds/dodsC/s3://aims-ereefs-public-prod/derived/ncaggregate/ereefs/gbr4_v2/daily-monthly/EREEFS_AIMS-CSIRO_gbr4_v2_hydro_daily-monthly-



This project uses the weekly dataset with the following variables:
- salinity (practical salinity unit)
- temperature (degrees Celcius)
- absolute height (meters)
- geostrophic zonal velocity from thermal wind equation (meters per second)
- geostrophic meridional velocity from thermal wind equation (meters per second)
- Mixed layer depth from density threshold equivalent to a 0.2°C
decrease (meters)

# Planned analysis: 

Figure 1 shows a basemap of the area considered in this project using cartopy.

Figure 2 investigates seasonal variability in the BoB by taking temporal means of SSH and SST across the different seasons.

Figure 3 investigates the relationship between mixed layer depth and SSH.

Figure 4 investigates the propagation of SSH anomalies, ultimately finding velocity.

Figure 5 shows a basemap of the area considered in this project using cartopy.

Figure 6 investigates seasonal variability in the BoB by taking temporal means of SSH and SST across the different seasons.

Figure 7 investigates the relationship between mixed layer depth and SSH.

Figure 8 investigates the propagation of SSH anomalies, ultimately finding velocity.
