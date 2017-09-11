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
`data/mtgs/data` directory, with the format `year_month.csv`. See the 
`2016_06.csv` file for an example 

* Create a spreadsheet with relevant usage hours data and save it 
to the `data/hrs/data` directory.  The current setup is for a summary
by domain by week. Depending on your 
system, you may have different accounting and may need to 
customize the usage code at the end of the report. 

* Create a ticket spreadsheet with the relevant ticket data in the 
`data/tickets/data` directory.  There is an example in the directory.  

## Generate Report

* Copy the `template.Rmd` file in the `reports` directory to a new file, named 
after the year/month of the report. 
* Change the values in the first R chunk to the appropriate year and month. 
* Add user highlights
* Fill out the second half of the report (Training, On- and Off- Campus partnerships)
* Use knitr (yarn button from RStudio interface) to generate report.  

See the `2016_06.Rmd` file for an example of a "completed" report, and `2016_06.html` for the rendered report.  
