# EnBirdWDI
#Endangered birds count
# Run the following first
library(devtools)
library(roxygen2)
library(raster)
library(rgdal)
library(WDI)
library(leaflet)
# Then install Through
devtools::install_github("tonyxuantong/EnBirdWDI")
# Test using
ENBird::WorldBankData_function()
