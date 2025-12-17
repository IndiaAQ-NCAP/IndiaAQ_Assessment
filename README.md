Assessment of Changes in Air Quality in Indian Cities Since the Launch of the National Clean Air Programme (NCAP)

Project Overview

This repository contains the analysis code used for the report “Assessment of Changes in Air Quality in Indian Cities Since the Launch of the National Clean Air Programme (NCAP)”.

The objectives of the assessment are to  
1.	Assess temporal trends in the levels of PM2.5 and PM10 across NCAP cities between 2017 and 2024.
2.	Develop a standardized and replicable framework for trend assessment in Indian cities that incorporates data quality filters, statistically sound trend detection methods, and meteorological adjustments, making it suitable for performance evaluation for the NCAP in the long term. 

The scope of the work is limited to the following parameters and methodological choices:
•	Time period: 2017–2024
•	Locations: 102 NCAP cities where CAAQMS data are available
•	Pollutants: PM₁₀ and PM2.5. Note the NCAP targets are set on the basis of PM10. 
•	Data type: Real-time data from CAAQMS is used; manual monitoring data is excluded. Furthermore, data from low-cost sensors was not used, in part because such data has not yet been used for regulatory applications in India and there remain specific quality assurance and quality control considerations. 
•	Methods: Air quality trends are assessed using individual station averages, not aggregated city-level averages. Station-level averages are used for the assessment over citywide averages, as variations in monitor operation such as shutdowns or restarts may distort overall values. They also ensure that localized pollution patterns are accurately represented.
•	Weather normalization is performed using a limited set of meteorological variables including temperature, boundary layer height, relative humidity, wind direction, wind speed, precipitation and atmospheric pressure to account for the influence of meteorology on pollutant levels.

Repository Contents
This repository contains only code. The data used in the analysis are not publicly available.
•	scripts/ – R scripts used for data processing, analysis, and visualization
•	README.md – Project documentation
•	Required R packages are listed within the scripts

Data Availability
The data used in this analysis are not publicly available and are therefore not included in this repository. This repository is intended to provide transparency and reproducibility of the analytical methods.

Report Reference
The full report is available at:
[ link]

If you have questions, please contact Abinaya Sekar at asekar@healtheffects.org or Adithi R. Upadhya at adithiru095@gmail.com. 

If you would like to contribute to the assessment, please submit a pull request.
