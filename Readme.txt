Data sources:

As the Cup of Excellence dataset is not public, the folders have been sanitised of any intermediate results featuring it.
The below instructions are included for illustrative purposes. 

The scraper may not be functional since changes were made to the CoE website. The code in its current form is not fully
executable, as the data files are missing.

---------------------------------------------------------------------------------------

Data cleaning using R scripts:

The scripts used for reproduction are in .rmd format and can be run using RStudio. 
HTML compilations are also included to be opened without R Studio.



Order of execution:
1. Scraper.rmd (3 hours)
2. Data cleaning.rmd (until the export block)
3. Applylexicon.rmd (1-1.5 hours)
4. Data cleaning.rmd (export block)

---------------------------------------------------------------------------------------

Analysis and modelling in Python:

Scripts are in .ipynb format and can be opened using Jupyter Notebook or Jupyter Lab.
HTML compilations included to be opened without a python installation.

The scripts are not co-dependent, can be ran in any order.

The analysis.ipynb file produces certain graphs used in the final report.

The modelling_framework.ipynb script contains bulk of the analysis. 
Full execution took ~16 hours on the author's computer (Intel i7-7700HQ CPU, 32GB RAM).
