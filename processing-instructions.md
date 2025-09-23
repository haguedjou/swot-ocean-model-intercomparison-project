# Processing instructions

Here, we explain how to prepare your dataset for this project.

1. Select the time period that you would like to share with us.

    - If your simulation includes the year 2024, please include it.
    -  Otherwise, it would be best to select a neutral year (i.e. a year without extreme events).
    - **IMPORTANT: If you contribute with more than 1 year, please prepared one dataset for each year**
    

2. Interpolate your simulation outputs onto SWOT grid, using [Synthocean](https://github.com/Amine-ouhechou/synthocean).

   - When interpolating the SWOT grid, if the year 2024 is not available, assume that the selected year corresponds to 2024 (using the dates closest to SWOT)

3. Please organize the files into separate folders for each cycle. Each folder should be named using cycle_XXX format, where XXX represents the three-digit cycle number (e.g., cycle_008, cycle_012).
> [!NOTE]  
> We expect to have a specific directory format and naming convention for each model output:
>  
> MODELNAME/cycle\_(cyclenumber)/MODELNAME\_GRID\_L3\_LR\_SSH\_(cyclenumber)\_(passnumber)\_(STARTDATE)\_(ENDDATE)\_v1.0.2.nc
> 
>(which is the same SWOT files format)
> 
4. Share your model data interpolated on SWOT grid through a S3 endpoint.
