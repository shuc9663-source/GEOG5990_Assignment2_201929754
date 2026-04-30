# GEOG5990_Assignment2_201929754
# Healthcare Access and Population Need Inequality across London MSOAs
## Background
This project aims to study the spatial inequalities in healthcare accessibility and population demands among the various mid-level super-output areas (MSOAs) in London. This analysis seeks to identify those areas where the population has high healthcare demands but the geographical accessibility to general practitioner services is poor. Identifying these areas is helpful for supporting local public health planning and prioritizing spatial issues, which can safeguard the public interest.
## Project aim
This code is designed to construct the index of service accessibility and demand priority for each MSOA in London through the calculation of data and the output of visual charts.
The project ultimately generates two visual charts: one is a non-spatial scatter plot, showing the relationship between population demand and accessibility of general practitioners. The other is a spatial color map, showing the service accessibility and demand priority index of each MSOA.
## Repository contents
The Repository contains the following contents: GEOG5990M_Final_Project.ipynb for storing the code, the README.md file, and the data folder.It includes:
London-MSOA-retailer-data.xlsx(Contains MSOA-level Census-derived variables to calculate population need indicators) 
epraccur.csv(NHS GP practice reference file. This is used to identify active GP practices and their postcodes)
gp-reg-pat-prac-all.csv(Patients Registered at a GP Practice dataset) 
ONSPD_2025_5_London.csv(London-filtered ONS Postcode Directory. This links GP practice postcodes to MSOA codes and coordinates)
London MSOA boundary data(provide the spatial boundaries for mapping the final priority index):msoa_boundaries.shp, msoa_boundaries.shx, msoa_boundaries.dbf, and msoa_boundaries.prj.
