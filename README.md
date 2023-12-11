# DATA 512 Final Project

## Project Goal 
The objective of this study was to investigate and quantify the impact of wildfire smoke on premature deaths within the city of Benicia, California. The research aimed to assess the correlation between exposure to wildfire smoke and the incidence of premature mortality in the region.  

## Data Source
The dataset that has been used for this analysis - https://www.sciencebase.gov/catalog/item/61aa537dd34eb622f699df81
This dataset is designed be to a comprehensive collection of fire boundaries within the United States and provides a more thorough and complete picture of fires across the United States when compared to the datasets that went into it.   
The datasets to be used were published by FRED, which is a database of over 267,000 economic time series from 80 sources. This dataset was created using data that has been published by the Centers for Disease Control and Prevention which is the national public health agency of the United States.  
The dataset contains the following columns:  
1. Date in YYYY-MM-DD format  
2. Age adjusted death rate
Poverty must be controlled for and so, data about Personal Income per capita was taken from US Census Data (FRED).
The following column was added to the final dataset:  
1. Per capita Personal Income
Links to the Datasets:
1. For Premature Death Rate: https://fred.stlouisfed.org/series/CDC20N2UAA006095  
2. For Per Capita Personal Income: https://fred.stlouisfed.org/series/PCPI06095
License: Custom - https://fred.stlouisfed.org/fred-addin/legal.html

## Documentation
In order to read in the wildfire data, the following example notebook provided by Professor David McDonald  was used under the CC-BY license.  
Example Notebook for Reading in the Wildfire Data - https://drive.google.com/file/d/1qNI6hji8CvDeBsnLDAhJXvaqf2gcg8UV/view  
We also used the GeoJSON reader provided by Professor David McDonald for the above purpose under the same licence.  
Link - https://drive.google.com/file/d/1TwCkvdaw0MxJzW7NSDg6XxYQ0dvaS44I/view   
CC-BY License - https://creativecommons.org/licenses/by/4.0/  

## Environment
Jupyter was used in order to run a .ipynb Notebook. Any editor that allows .ipynb notebooks can be used to run this project following the installation of the modules specified in the code.

## License
This project is open-source and follows the MIT License. You are free to use and modify the code following the terms of the MIT License.

## Steps to Reproduce:
1)	Install and import the necessary Python libraries.  
2)	Run the Jupyter notebook which contains the code to retrieve the data from the google document and the APIs, preprocess it, upload it into the output files and create the necessary visualizations. 

## Limitations  
The specific causes of death are not provided in the dataset. Knowing the leading causes of death for each year can help interpret the age-adjusted death rates more comprehensively. Further, the data being used for this study only covers the last 20 years and has been restricted to the city of Benicia, CA. 




