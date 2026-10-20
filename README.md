# educational-resources-pisa2018-analysis

An econometric analysis and investigation into the effects of home resources on academic performance across mathematics, reading and science tests. Achieved via visualisations and OLS regressions on a PISA 2018 UK dataset. 

## Research overview
This project investigates how material differences in the home (such as access to the internet and computers) impact exam results across subjects. Using the PISA 2018 UK dataset, this project isolates and quantifies the significance of individual home environment variables, while controlling for gender, wealth and parental education (hisced) to minimise OVB.

## Key findings 

Home internet access: identified as the most influential home resource of those investigated, with a positive coefficient ranging from 78-83 across all 3 subjects. 

Home Computers: found to have a positive coefficient ranging from 15-22, demonstrating a positive impact on learning outcomes, though not of huge significance, likely because once isolated from internet access, the utility provided by a home computer is harshly limited.

Textbooks (defined as 'books' within the study): found to have a positive coefficient ranging from 9- 14, demonstrating that they serve some degree of utility, but are largely inconsequential. 

## Methodology 
Language: Python, Jupyter Notebook
Libraries: pandas, statsmodels, numpy, scipy, matplotlib 
Models: Ordinary Least Squares (OLS) regressions with dummy variables for categorical resource brackets 

## Repository structure

PISA2018_code.ipynb - full script for data cleaning, visualisations (histograms, bar charts, and boxplots) and regressions

PISA2018_full_analysis - full in-depth report and review of results 

PISA-2018-GBR.csv - raw dataset used in analysis 

