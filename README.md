# **ENVI5809-Final-Project**
**Thermal Limitation of Seagrasses in Great Barrier Reef Ecosystem**

The thermal limitation of seagrasses related to the light, temperature directly and pH indirectly.

In this case, we organized to compare the temperature differences between different water depth, the seasonal temperature differences and the pH differences. After that, the current speed and direction with the thermal transfer has been concerned. As a result, we hope to figure out the trend of the seagrasses Survivorship in globaling warming environment. 

# **Data:** 
We use three dataset in the eReef database:

**For temperture analysis** 
- https://thredds.ereefs.aims.gov.au/thredds/dodsC/GBR4_H2p0_B3p1_Cq3b_Dhnd/monthly.nc

**For pH and current speed and direction analysis:**
- http://thredds.ereefs.aims.gov.au/thredds/dodsC/s3://aims-ereefs-public-prod/derived/ncaggregate/ereefs/GBR4_H2p0_B3p1_Cq3b_Dhnd/daily-monthly/EREEFS_AIMS-CSIRO_GBR4_H2p0_B3p1_Cq3b_Dhnd_bgc_daily-monthly-2019-01
- http://thredds.ereefs.aims.gov.au/thredds/dodsC/s3://aims-ereefs-public-prod/derived/ncaggregate/ereefs/gbr4_v2/daily-monthly/EREEFS_AIMS-CSIRO_gbr4_v2_hydro_daily-monthly-2019-01

The meaning of the model name of GBR4_H2p0_B3p1_Cq3b_Dhnd: 
- GBR4: Great Barrier Reef model with a grid of approximately 4 kilometres resolution.
- H2p0: Hydrodynamic model version 2.0
- B3p1: Biogeochemical model version 3.1
- Cq3b: Catchment model using load specification q3b. P2R SOURCE Catchments with 2019 catchment condition from Dec 1, 2010 - 30/6/2018 (used for GBR Report Card 8 published in 2019), Empirical SOURCE with 2019 catchment  condition, Jul 1, 2018 - April 30, 2019.
- Dhnd: Model deployment - Hindcast

**This project uses the datasets with the following variables:**
- water depth (zc, meter)
- date (time, day-month-year)
- pH (PH, log(mM))
- temperature (temp, degrees Celcius)
- current speed and direction (mean_cur, ms-1)

# **Planned analysis:** 

Figure 1-3 summer (2019/01/31) temperature  at water depth of -0.5m, -5.5m and -39.5m in entire great barrier reef;

Figure 4-6 summer temperature at water depth of -0.5m, -5.5m and -39.5m at study region (Princess Charlotte Bay) and two sites (the subtital and intertidal);

Figure 7-8 winter (2018/07/31) temperature at water depth of -0.5m in entire great barrier reef and study region with two sites;

Figure 9-10 summer pH at water depth of -0.5m in entire great barrier reef and study region with two sites;

Figure 11 summer current speed and direction at water depth of -0.5m at study region with two sites. 

# **Binder Link**

