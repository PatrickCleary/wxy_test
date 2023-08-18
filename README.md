# WXY Test

To run:

1. Download permit issuance data from: https://data.cityofnewyork.us/Housing-Development/DOB-Permit-Issuance/ipu4-2q9a
2. place in the root of this directory with file name: `DOB_Permit_Issuance.csv`
3. run `jupyter notebook` from root.

There are 3 files.

1. `basic_analysis` – This is the summary metrics and 3 graphs of different datapoints.
2. `spatial_join` – This is the work to do a spatial join. I joined the permits with the flood zones from Hurricane Sandy and did some analysis on that.
3. `slope_zip_code` – This is an extra thing I wanted to check out. I calculated the linear trend of building permits being issued by zip code. Then created a map to show which areas had the highest increases/decreases since 1989.
