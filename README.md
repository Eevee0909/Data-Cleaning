# Data-Cleaning
Saving R code used in projects for data cleaning

# set up work directory

setwd('G:/DATA/--/Projects')

# read an excel file in folder
library(readxl)

df = read_excel('IMF.Econ.Stats.cleaned.xlsx', sheet = 'economic_data', skip = 0)
