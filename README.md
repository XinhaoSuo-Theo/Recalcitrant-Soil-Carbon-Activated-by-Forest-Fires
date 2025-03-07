# Recalcitrant-Soil-Carbon-Activated-by-Forest-Fires
The original code was derived from the Carbon-Nitrogen (CN) module within the Community Land Model (CLM). We introduced a new variable i_soil42 and implemented an additional loop to characterize the activation process of inert carbon following wildfires. 
This modified code was then integrated into the Community Earth System Model (CESM) and executed. 
We set the compset as I1850Clm45CN,xmlchange DATM_CLMNCEP_YR_START=1991，xmlchange DATM_CLMNCEP_YR_END=2010，xmlchange STOP_OPTION=nyears,STOP_N=600,NTASKS=164
And setoutput:
hist_fincl1='FCO2','LITR1C_TO_SOIL1C','LITR1N_TO_SOIL1N','LEAFC_TO_LITTER','SOIL1C','SOIL2C','SOIL3C','TOTSOMC','TOTLITC','LITTERC_LOSS','LEAFC_TO_LITTER','LITTERC_HR','TOTVEGC','TOTECOSYSC','GPP','NEP','TLAI','NPP','NBP','BGNPP','DISPVEGC','DWT_CONV_CFLUX','DWT_CONV_CFLUX_DRIBBLED','HR','LITR1C','LITR2C','LITR3C','LITTERC_HR','MR','SR','STORVEGC','NEE','TOTECOSYSC','FCH4'
