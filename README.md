# Monthly U.S. Import Data

This repo contains monthly U.S. imports at the HS 10 level. 

The file `data benchmarks.ipynb` compare the aggregate data from this dataset to the aggregates posted by Census at https://www.census.gov/foreign-trade/balance/c0015.html. From 2015--onward the two are virtually identical. Pre-2013 the differences are mostly small, with the exception of March 1990. I need to look into that month. 

### 1990-2012
These files are from the Census Bureau CDs, which were accessed from the Wisconsin Historical Society library, but are available broadly. The unit of observation is

```Year-Month-HS10-Country-Country_subcode-District_entry-District_unlading-Rate_provision_code```

The files `imp_detl.dbf` contain the data in the 1990-2008 discs. The fixed-width files `imp_detl.txt` contain the data and `imp_detl.str` contain the layout in the 2009-2012 discs.

### 2013-
These files were downloaded from the Census Bureau API. The unit of observation is

``Year-Month-HS10-Country```
