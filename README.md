# DeAD_LPI_transects_quadrats

This repository contains shared documentation, code, derived data files, results files, and figures for the analysis of modified line point-intercept (LPI) transect and litter quadrat data collected at the Santa Rita Experimental Range (SRER), Onaqui (ONAQ), Moab (MOAB), and Jornada Experimental Range (JORN) National Ecological Observatory Network (NEON) sites in Fall 2024 and Spring 2025.

GPS coordinates were taken using a SparkFun real-time kinematic (RTK) Express global navigation satellite system (GNSS) mounted to a 1.74 m monopole. Data for each transect were recorded in a unique project in the SW Maps Application on an iPad. Drop-down menus were used for primary fields and free-form text was used for "other" fields.

Data collection methods are described in greater detail in the Fall_2024_Transects_Data_Cleaning.qmd and Spring_2025_Transects_Data_Cleaning.qmd files within the "code" folder. These files are set up to pull raw data files from a Dropbox folder owned and maintained by Heather Throop.

This repository is structured with the following folders:
code - contains .qmd files for data cleaning and analysis
output - contains all output files generated in the .qmd files organized into subfolders
  data_files - contains derived data files and sample logs
  figures - contains figures 
  result_files - contains result files from statistical tests
  
This repository involves the following data levels:
L0 - individual csv files for each transect; not stored here; pulled in directly from the Dropbox folder owned and maintained by Heather Throop
L1 - compiled csv file containing data for all transects; generated once here, then subsequently pulled in directly from the Dropbox folder owned and maintained by Heather Throop
L2 - compiled and cleaned csv file containing data for all transects (with replicate data points and data points containing irreconcilable typos or other mistakes removed), transect locations csv file, quadrat sample log csv file; stored in output > data_files > L2
L3 - summary and other derived data csv files; stored in output > data_files > L3

For further information regarding this repository, please contact: Alexi Besser (acbesser@asu.edu)
