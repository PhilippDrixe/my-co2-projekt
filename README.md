For an overview of the data preparation, data merge and modelling in the co2 project
check the PowerPoint file 
Liora_Project_CO2-Emissions_v17.pptx

The full process of data processing and merging is included in 
Project_co2_DataPreparation_DataMerge.ipynb
which produces the df_model.csv datafile for further analysis and modelling:
df_model.csv requires weighting with variable r_merged to roughly represent 2013 sales volumes
and approx. market shares, as well as filtering brand_comp==both
to combine and take advantage of both datasets

All further files include the modelling part of this project
