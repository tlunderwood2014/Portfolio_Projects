# Ames Real Estate Analysis

## Table of Contents

[Problem Statement](https://github.com/tlunderwood2014/Portfolio_Ames/README/#Problem-Statement)
[Data Dictionary](https://github.com/tlunderwood2014/Portfolio_Ames/README/#Data-Dictionary)


## Problem Statement:
Investor A is interested in buying investment properties in Ames, Iowa. Their goal is to buy, renovate and resale these properties. In order to successful understand the housing market in Ames, they want to know which features will increase their profit margin.  A regression model will be created to understand the relationship between the features and the property value.

## Summary


#### Data Source:


## Data Dictionary:
 


|Feature|Type|Dataset|Description|
|---|---|---|---|
|Order|int64|Ames Iowa Housing Dataset|Observation number|
|PID|Int64|Ames Iowa Housing Dataset |Parcel identification number|
|MS SubClass|int64|Ames Iowa Housing Dataset| The building class|
|MS Zoning|object|Ames Iowa Housing Dataset| general zoning|
|Lot Frontage|float64|Ames Iowa Housing Dataset|Linear feet of street connected to property|
|Lot Area|int64|Ames Iowa Housing Dataset|Lot size in square feet|
|Street|object|Ames Iowa Housing Dataset|Type of road access to property|
|Alley|object|Ames Iowa Housing Dataset|Type of alley access to proerty|
|Lot Shape|object|Ames Iowa Housing Dataset|General shape of property|
|Land Contour|object|Ames Iowa Housing Dataset|Flatness of the property|
|Utilities|object|Ames Iowa Housing Dataset|Type of utilities available|
|Lot Config|object|Ames Iowa Housing Dataset|Lot configuration|
|Land Slope|object|Ames Iowa Housing Dataset|Slope of property|
|Neighborhood|object|Ames Iowa Housing Dataset|Physical locations within Ames city limits|
|Condition 1|object|Ames Iowa Housing Dataset|Proximity to main road or railroad|
|Condition 2|object|Ames Iowa Housing Dataset|Proximity to main road or railroad (if second is present)|
|Bldg Type|object|Ames Iowa Housing Dataset|Type of dwelling|
|House Style|object|Ames Iowa Housing Dataset|Style of dwelling|
|Overall Qual|int64|Ames Iowa Housing Dataset|Overall material and finish quality|
|Overall Cond|int64|Ames Iowa Housing Dataset|Overall condition rating|
|Year Built|int64|Ames Iowa Housing Dataset|Original construction date|
|Year Remod/Add|int64|Ames Iowa Housing Dataset|Remodel date|
|Roof Style|object|Ames Iowa Housing Dataset|Type of roof|
|Roof Matl|object|Ames Iowa Housing Dataset| Roof material|
|Exterior 1st|object|Ames Iowa Housing Dataset|Exterior covering on house|
|Exterior 2nd|object|Ames Iowa Housing Dataset|Exterior covering on house (if more than one material)|
|Mas Vnr Type|object|Ames Iowa Housing Dataset|Masonry veneer type|
|Mas Vnr Area|float64|Ames Iowa Housing Dataset|Masonry veneer area in square feet|
|Exter Qual|object|Ames Iowa Housing Dataset|Evaluates the quality of the material on the exterior|
|Exter Cond|object|Ames Iowa Housing Dataset|Evaluates the present condition of the material on the exterior|
|Foundation|object|Ames Iowa Housing Dataset| Type of foundation|
|Bsmt Qual|object|Ames Iowa Housing Dataset|Evaluates the height of the basement|
|Bsmt Cond|object|Ames Iowa Housing Dataset|Evaluates the general condition of the basement|
|Bsmt Exposure|object|Ames Iowa Housing Dataset|Refers to walkout or garden level walls|
|BsmtFin Type 1|object|Ames Iowa Housing Dataset|Rating of basement finished area|
|BsmtFin SF 1|float64|Ames Iowa Housing Dataset|Type 1 finished square feet|
|BsmtFin Type 2|object|Ames Iowa Housing Dataset|Rating of basement finished area (if multiple types)|
|BsmtFin SF 2|float64|Ames Iowa Housing Dataset|Type 2 finished square feet|
|Bsmt Unf SF|float64|Ames Iowa Housing Dataset|Unfinished square feet of basement area|
|Total Bsmt SF|float64|Ames Iowa Housing Dataset|Total square feet of basement area|
|Heating|object|Ames Iowa Housing Dataset|Type of heating|
|Heating QC|object|Ames Iowa Housing Dataset|Heating quality and condition|
|Central Air|object|Ames Iowa Housing Dataset|Central air conditioning|
|Electrical|object|Ames Iowa Housing Dataset|Electrical system|
|1st Flr SF|int64|Ames Iowa Housing Dataset|First Floor square feet|
|2nd Flr SF|int64|Ames Iowa Housing Dataset|Second floor square feet|
|Low Qual Fin SF|int64|Ames Iowa Housing Dataset|Low quality finished square feet (all floors)|
|Gr Liv Area|int64|Ames Iowa Housing Dataset|Above grade (ground) living area square feet|
|Bsmt Full Bath|float64|Ames Iowa Housing Dataset|Basement full bathrooms|
|Bsmt Half Bath|float64|Ames Iowa Housing Dataset|Basement half bathrooms|
|Full Bath|int64|Ames Iowa Housing Dataset|Full bathrooms above grade|
|Half Bath|int64|Ames Iowa Housing Dataset|Half baths above grade|
|Bedroom AbvGr|int64|Ames Iowa Housing Dataset|Bedrooms above grade (does NOT include basement bedrooms)|
|Kitchen AbvGr|int64|Ames Iowa Housing Dataset|Kitchens above grade|
|Kitchen Qual|object|Ames Iowa Housing Dataset|Kitchen quality|
|TotRms AbvGrd|int64|Ames Iowa Housing Dataset|Total rooms above grade (does not include bathrooms)|
|Functional|object|Ames Iowa Housing Dataset|Home functionality (Assume typical unless deductions are warranted)|
|Fireplaces|int64|Ames Iowa Housing Dataset|Number of fireplaces|
|Fireplace Qu|object|Ames Iowa Housing Dataset|Fireplace quality|
|Garage Type|object|Ames Iowa Housing Dataset|Garage location|
|Garage Yr Blt|float64|Ames Iowa Housing Dataset|Year garage was built|
|Garage Finish|object|Ames Iowa Housing Dataset|Interior finish of the garage|
|Garage Cars|float64|Ames Iowa Housing Dataset|Size of garage in car capacity|
|Garage Area|float64|Ames Iowa Housing Dataset|Size of garage in square feet|
|Garage Qual|object|Ames Iowa Housing Dataset|Garage quality|
|Garage Cond|object|Ames Iowa Housing Dataset|Garage condition|
|Paved Drive|object|Ames Iowa Housing Dataset|Paved driveway|
|Wood Deck SF|int64|Ames Iowa Housing Dataset|Wood deck area in square feet|
|Open Porch SF|int64|Ames Iowa Housing Dataset|Open porch area in square feet|
|Enclosed Porch|int64|Ames Iowa Housing Dataset|Enclosed porch area in square feet|
|3Ssn Porch|int64|Ames Iowa Housing Dataset|Three season porch area in square feet|
|Screen Porch|int64|Ames Iowa Housing Dataset|Screen porch area in square feet|
|Pool Area|int64|Ames Iowa Housing Dataset|Pool area in square feet|
|Pool QC|object|Ames Iowa Housing Dataset|Pool quality|
|Fence|object|Ames Iowa Housing Dataset|Fence quality|
|Misc Feature|object|Ames Iowa Housing Dataset|Miscellaneous feature not covered in other categories|
|Misc Val|int64|Ames Iowa Housing Dataset|Value of miscellaneous feature|
|Mo Sold|int64|Ames Iowa Housing Dataset|Month Sold (MM)|
|Yr Sold|int64|Ames Iowa Housing Dataset|Year Sold (YYYY)|
|Sale Type|object|Ames Iowa Housing Dataset|Type of sale|
|SalePrice|int64|Ames Iowa Housing Dataset|Sale price $$|
|--------|-----|------|------|

Citation : Joe Rosenblum helped with the data dictionary

## Software Requirements/Packages Used
- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- tensorflow
- keras

## Exploratory Data Analysis


## Modeling




## Conclusion/ Limitations:
Five Neighborhood to consider: Stone Brook, Northridge Heights, Crawford, Timberland, and Veenker
Maximize Profit features :  Fireplaces, Overall house quality,  Northridge Neighbor, Full bath in basement
Features to avoid: Not having a  fireplace, Exterior upgrades, Normal Kitchen quality, Unfinished Garages, as years increase prices decrease



