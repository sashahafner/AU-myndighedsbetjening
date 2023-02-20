# 2021-0220838_NH3_EF_solid_manure
Estimation of emission factors for ammonia volatilization from field-applied solid manure.

# Overview
This task included a compilation of literature data on ammonia loss from field-applied solid manure from cattle, pigs, and poultry.
The files in this directory include the extracted literature data, plots, and numeric summaries of the results, and R scripts for generating the results.

# Repeating calculations
Calculations can be repeated by running the script `scripts/main.R` in R.
See below for more details on the contents of individual directories.

# Directories
## `data`
* `lit_com.xlsx` is a Microsoft Excel file with emission data extracted from the literature
* `norm_comp.csv` is a comma-separated text file with manure composition from the Danish normative system

## `functions`
R functions used in data analysis.
Most of these are from <https://github.com/sashahafner/jumbled/>.

## `logs`
A single text file with a log of the software versions of R and add-on packages last used to generate results.

## `output`
Results from the analysis.
See section below on linking results to the memo for more details.

## `plots`
Plots used in the memo or for simply viewing data.
See section below on linking results to the memo for more details.

## `scripts`
R scripts for generating results.
The script `main.R` shows the order scripts are called used to process literature data and generate results.
By running this script in R (<https://www.r-project.org/>) the complete analysis is carried out.

# Links to memo