Notes for the users -- for exceptions, special model behavior, treatment of regridding etc. 

* The variable netTOA is derived from rlut,rsdt,rsut for all models, but CCSM3 for which flnt and fsnt are used

* CCSM3 first years are out of equilibrium, both control and simulations drift a lot (more than a degree), so don't take the anomaly as mean of the control simulation, but year by year, for the first few (~20) years

* rsdt has years which are 1W/m2 off in CCSM around year 1900 of the experiment and ECHAM5 around year 3900 and 4100 of the experiment 

* ECHAM5 abrupt 4x missing years (or put in NA); for atmosphere, missing years are [3483, 3484, 3485, 3486, 3487, 3488, 3489, 3490, 3491, 3560, 3561, 3562, 3563, 3564, 3565, 3566, 3567, 3568, 3569, 3570, 3571, 3572, 3573, 3574, 3575, 3576, 3577, 3578, 3579, 3580, 3581, 3582, 3583, 3584, 3585, 3586, 3587, 3588, 3589, 3590, 3591, 3592, 3593, 3594, 3595, 3596, 3597, 3598, 3599, 3621, 3783, 3806, 3808, 3810, 3815, 3820, 3825, 3827, 3832, 3834, 3844]

* The ECEARTH runs don't have eccentricity. But they do have a melting Greenland ice sheet. Seems like, energy is not conserved (or goes into the melding ice?)

* GISS control has some discrepencies; the months line up as follows:
  tas,rlut           | 1-3600 | 3601-66300
  rlutcs,rsut,rsutcs |        |     1-62700

For the GFDL models the 150 year control simulation is the same as the submitted long control simulation and just provided to make anomalies etc. easier to compute. 
For the GFDL models the 150 year abrupt4x and control simulations stem from the ETH CMIP5 database and come regridded already. 

* HadCM3L has a jump of about 80W/m2 in surface heat fluxes constructed by atmospheric variables hfls, hfss, rls, rsds, rsus after 800 years of control.  

