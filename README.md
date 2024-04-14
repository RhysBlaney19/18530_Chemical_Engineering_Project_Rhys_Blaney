# 18530_Chemical_Engineering_Project_Rhys_Blaney
Harvested CO2 and N2 adsorption data from the NIST, IAST calculations, and pure and binary simulation data 

The Excel files, named 'MOF_name'_CO2_experimental_adsorption_data, contain the CO2 harvested data from the NIST-ISODB. The first sheet in each file contains information such as the DOI for each source, whether N2 data is also available, and other general comments specific to the data entry. The second sheet contains the scaled and fitted isotherm data for each entry. Statistical analysis is carried out in this sheet to determine the outlier isotherms. The third sheet is the same as the second sheet but minus the outlier isotherms. The average experimental isotherm used in the report is taken from this sheet. The subsequent sheets contain the raw experimental data for each entry. The scaling and fitting of the data set is carried out in these sheets. 

Similarly, the Excel files, named 'MOF_name'_N2_experimental_adsorption_data, contain the N2 harvested data from the NIST-ISODB. The first sheet contains conversion factors. The subsequent sheets contain the experimental N2 adsorption data, and the saturation adsorption value is calculated in these sheets.

The 'Pure_CO2_GCMC_simulations' file contains the adsorption simulation data for each of the three MOFs. 

The 'Binary_CO2_CH4_simulations_IAST_adsorption_data' file contains the predicted adsorption values for a 60% CH4 and 40% CO2 binary adsorption system calculated by GraphIAST, as well as the adsorption values generated by GCMC simulations, for CuBTC and MOF-5.
