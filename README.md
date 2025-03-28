## ML Foundation Course Mini Project ##
#### K-means Clustering of Amazon Climatological Data to Determine Representative Regions ####
Author: Emily Wright - Graduate Trainee (emily.wright@metoffice.gov.uk)

Supervisor: Theo Economou (t.economou@exeter.ac.uk)

Training scoped and funded as part of the Transatlantic Data Science Academy

**Aim:**  Use ML clustering techniques to group together similar areas of the Amazon based on climatological and geological input data

**Use Case:** 
- Be able to use a few ‘representative points’ to model the whole amazon
- Understand how representative the AmazonFACE site is of the rest of the amazon
    - could lead to suggestions of future sites
    - could be used to bias correct data from current site to represent other locations

**Method:** 
- Data wrangling: handling NaNs, removing invalid data, logging data, normalisation
- k-means clustering (using elbow method to determine k)

**Results/Analysis:**
5 clusters (see plot on right). Note AmazonFACE site in region 4 but borderline region 0, suggesting high temp, high precip and med/low phos

**Next Steps:** 
- Consider using more variables such as; Palmer Drought Severity Index, Above Ground Biomass, water table depth
- Consider using other clustering algorithms (and compare)
