# Monthly Reports for Research Computing Facilitation

## Getting Started

0. Install R and RStudio if you don't already have them.  
1. Make sure you have the following libraries installed: 
  * dplyr
  * ggplot2
  * knitr
  * tidyr
2. Clone this repository.
3. Open RStudio and start a new project based on the cloned 
repository ("Create project from existing directory").
4. Follow the steps below to prepare your reports.  

## Data Preparation

* Create a spreadsheet with a list of engagements, saved in the 
`data/eng` directory, with the format `year_month.csv`. See the 
`2016_06` file for an example 

> Christina enters engagements into a Google form to generate 
these spreadsheets.  

* Create a spreadsheet with relevant usage hours data and save it 
to the `data/hrs` directory.  The current setup is for a summary
by domain by week and overall usage per month (see the `data/hrs` 
directory for samples).  Depending on your 
system, you may have different accounting and may need to 
customize the usage code at the end of the report. 

## Generate Report

* Copy the `template.Rmd` file in the `reports` directory.  
* Change the values in the first R chunk to the appropriate year and day. 
* Use you ticket system to find out how many new tickets were created in the month and 
fill in the first R chunk.  
* Add user highlights
* Fill out the second half of the report.  
* Use knitr (yarn button from RStudio interface) to generate report.  

See the `2016_06.Rmd` file for an example of a "completed" report, and `2016_06.html` for the rendered report.  
