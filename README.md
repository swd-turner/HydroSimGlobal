# HydroSimGlobal
Simulation results for 1593 hydropower dams under historical and projected 21st century climate conditions

#### NOTE
The official repository for these data is now hydroshare: https://www.hydroshare.org/resource/90628426e37c4c83b8e45527cece6fdd/


Further details of each dam (location, installed capacity, etc.) can be obtained by linking to the relevent GRanD database ID, given in GRanD_ID.csv in the main directory.

Data files can be read easily in R using (e.g.):

> load(".../20th Century Simulations/Power_1906_2000")

All data are in monthly time series. The 20th century simulations are saved as a multi time series (mts) object for the period 1906 - 2000 (1140 months * 1593 dams). The GCM-forced simulations are saved as lists with multiple time series for each dam, representing storage, release, power and so on.
