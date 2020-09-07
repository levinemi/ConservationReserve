# ConservationReserve
Interactive Map of Conservation Reserves and Boat Launches in Ontario

Shape Files 
- Conservation_Reserve_Regulated.shp
- Fishing_Access_Point.shp

Additional files
- policyreports_conservationreserve.csv (this is the output from the webscraping; this file can be loaded instead of running the policy report scraping function)

Process
1. Download the files to a directory and set the workind directory in R.
2. Run the "Map_of_CRs.Rmd" file
3. Note - you can create the map either by running the RMD file as is or, you can run Chunks 1-5 & 10-13. If you choose the second option, remove " eval=FALSE" from the chunk header.
