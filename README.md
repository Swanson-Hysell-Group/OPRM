# OPRM
This repo is for compiling and analyzing Applied Physics OPRM measurements and compare with SQUID SRM data



### OPRM_SRM_comparison.ipynb

This notebook contains all code for file conversion and data analyses.



### Figures

This folder includes figure export from Jupyter notebook.



### OPRM_data

This folder includes the raw .csv data files from the OPRM. Note for each temperature step we made multiple measurement on the OPRM.



### OPRM_data_CIT

This folder includes OPRM raw data converted to CIT format using the code in the notebook. The CIT files are then processed to be in MagIC data format such that one can use the Pmag GUI to make least-squre fits and export other statistics. No averaging is performed upon the raw data. 



###  OPRM_data_CIT_average

This folder includes OPRM raw data converted to CIT format using the code in the notebook. The CIT files are then processed to be in MagIC data format with averaging. Least-squre fits are then performed and associated statistics are exported.



### SRM_data

This folder includes raw superconducting rock magnetometer files in CIT format. The files are converted to MagIC format. Least-squre fits are performed and associated statistics are exported.

