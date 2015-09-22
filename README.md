# fcat_biomass
Development of a biomass framework for the California Forest Climate Action Plan

## Harvested Wood Products
Harvested wood products data comes from [McIver *et. al.* (2012)](https://docs.google.com/uc?id=0B9-9Vlx0SkkFMkhFZUN5X2djbms&export=download). The following tables have been created:

* **Harvest end-use by year** (MMBF Scribner) assumes that end use fractions presented in McIver (Figure 6) from 2012 apply historically. This assumtion is likely to underrepresent bioenergy, paper and engineered wood products and overemphasize mulch and soil as California's forest products industry has lost much of its secfondary processing capacity as well as its bioenergy infrastrucutre. [link to table](https://github.com/peteWT/fcat_biomass/blob/56770d7d2cd5a38b5f592a45cbcb74d133c7e53f/pd/hrv_by_enduse.csv)
* **Ten-year moving average harvest by by lanowner** (MMBF Scribner) Shows average of harvest and standard deviation for ten year moving windows by ownership category. [link to table](https://github.com/peteWT/fcat_biomass/blob/56770d7d2cd5a38b5f592a45cbcb74d133c7e53f/pd/tenyear_harv.csv)